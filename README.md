# AI-Detective-Game

A web-based detective game built with **Next.js**, **TypeScript**, **React**, and **Tailwind CSS**.

## Installation (Mac)

Follow the steps below to set up the development environment on macOS.  

### 1. Install Homebrew
[Homebrew](https://brew.sh/) is a package manager for macOS. Install it by running:  
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### 2. Install Node.js
Use Homebrew to install Node.js, a cross-platform JavaScript runtime, by running `brew install node`.

### 3. Verify Installation
Confirm that Node.js and npm (Node’s package manager) are installed by running `node -v` and `npm -v`. You should see version numbers displayed for both commands.

### 4. Install Dependencies
After cloning this repository, navigate into the project folder and install dependencies: `npm install`.

## Usage

1. Run the development server:
```bash
npm run dev
```

2. Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

## Project Structure
```
ai-detective-game/
├── src/
│   ├── app/          # Next.js App Router pages
│   ├── components/   # Reusable UI components
│   └── styles/       # Global and Tailwind styles
├── public/           # Static assets
├── package.json      # Project dependencies & scripts
└── tailwind.config.ts
```