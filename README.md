# lighthouse-nodejs
Use Lighthouse as a Node module to programmatically to audit, record and compare web performance metrics.

This will generate the lighthouse JSON report for specified URL and store it in reports directory. The generated report can be viewed using https://googlechrome.github.io/lighthouse/viewer2x/.

## How to use

### Clone the repo
```
git clone https://github.com/subhra44/lighthouse-nodejs.git
```

### Install dependencies
```
npm install
```

### Run below command to generate the report
```
node lh.js --url http://subhra.me/
```

### How to view the report
Go to https://googlechrome.github.io/lighthouse/viewer/
Upload the generated JSON file

## References
Script is written based on the below article.
https://css-tricks.com/build-a-node-js-tool-to-record-and-compare-google-lighthouse-reports/
