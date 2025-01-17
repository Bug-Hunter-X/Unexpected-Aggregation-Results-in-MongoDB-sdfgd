# Unexpected Aggregation Results in MongoDB

This repository demonstrates a common error encountered when using MongoDB aggregation pipelines. The original query produces unexpected results due to an incorrect pipeline stage order or missing stages. The solution provides a corrected pipeline to accurately aggregate data. 

## Bug Description

The provided aggregation pipeline intends to group documents, sort by count, and limit the results to the top 10. However, due to the incorrect ordering or missing stages, the results are inaccurate. 

## Solution

The solution offers a corrected aggregation pipeline to produce accurate results.