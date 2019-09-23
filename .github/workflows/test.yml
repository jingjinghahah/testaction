name: CI
on: [push]
jobs:
  build-qq-ci:
    runs-on: ubuntu-latest
    steps:
    - name: Checkout
      uses: actions/checkout@master

    - name: Build
      uses: qq-miniapp/build:latest
      env:
        VERSION: 1.5.8
        DESC: CI自动构建上传1111
        APPTOKEN: b1dc5aab833af6a21118bbfa10e82f64
        BUILDUSER: ${{ GITHUB_ACTOR }}
        EXPERIENCE: true