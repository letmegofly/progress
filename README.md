# progress
2022年启动阅读计划

Get Help
GitHub Issues for bug report and feature requests
Email dev@echarts.apache.org for general questions
Subscribe to the mailing list to get updated with the project
Build
Build echarts source code:

Execute the instructions in the root directory of the echarts: (Node.js is required)

# Install the dependencies from NPM:
npm install

# Rebuild source code immediately in watch mode when changing the source code.
npm run dev

# Check correctness of TypeScript code.
npm run checktype

# If intending to build and get all types of the "production" files:
npm run release
Then the "production" files are generated in the dist directory.

Contribution
If you wish to debug locally or make pull requests, please refer to the contributing document.
