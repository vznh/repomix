# Installation

## Using npx (No Installation Required)

```bash
npx repomix
```

## Global Installation

### npm
```bash
npm install -g repomix
```

### Yarn
```bash
yarn global add repomix
```

### Homebrew (macOS)
```bash
brew install repomix
```

## Docker Installation

Pull and run the Docker image:

```bash
# Current directory
docker run -v .:/app -it --rm ghcr.io/yamadashy/repomix

# Specific directory
docker run -v .:/app -it --rm ghcr.io/yamadashy/repomix path/to/directory

# Remote repository
docker run -v ./output:/app -it --rm ghcr.io/yamadashy/repomix --remote yamadashy/repomix
```

## System Requirements

- Node.js: ≥ 18.20.0
- Git: Required for remote repository processing

## Verification

After installation, verify that Repomix is working:

```bash
repomix --version
repomix --help
```
