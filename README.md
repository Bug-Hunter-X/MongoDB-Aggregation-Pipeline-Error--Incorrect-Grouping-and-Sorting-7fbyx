# MongoDB Aggregation Pipeline Error
This repository demonstrates a common error in MongoDB aggregation pipelines: incorrect grouping and sorting leading to unexpected results. The `bug.js` file shows the faulty pipeline, while `bugSolution.js` provides the corrected version.

## Problem Description
The initial aggregation pipeline attempts to group documents by a field, count occurrences, sort by count, and limit the results.  However, a missing stage leads to inaccurate aggregation.

## Solution
The solution adds the necessary stage to correct the aggregation process.