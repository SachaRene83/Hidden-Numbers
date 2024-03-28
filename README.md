# Hidden-Numbers
on:
  push:
    branches:
      - $default-branch

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Checkout code
        uses: actions/checkout@v4
      - name: Run tests
        run: echo "Running tests..."
