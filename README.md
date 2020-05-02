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

### Run below command to generate the report and compare with the previous report (if exists)
```
node lh.js --url http://subhra.me/
```

### Run below command to compare two different reports
```
node lh.js --from reports/subhra.me/2020-04-29T17_35_22.373Z --to reports/subhra.me/2020-05-01T17_09_11.665Z
```

### How to view the report
Go to https://googlechrome.github.io/lighthouse/viewer/
Upload the generated JSON file