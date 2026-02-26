name: Release Obsidian Theme

on:
  push:
    tags:
      - "*"

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout
        uses: actions/checkout@v3

      - name: Create release archive
        run: |
          zip Press-Cute.zip theme.css manifest.json

      - name: Create GitHub Release
        uses: softprops/action-gh-release@v1
        with:
          files: |
            Press-Cute.zip
            manifest.json
            theme.css
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
