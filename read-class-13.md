Read
Mongo Aggregations
    -The aggregation pipeline is a framework for data aggregation modeled on the concept of data processing pipelines. 
    - db.orders.aggregate([
   { $match: { status: "A" } },
   { $group: { _id: "$cust_id", total: { $sum: "$amount" } } }
])
First Stage: The $match stage filters the documents by the status field and passes to the next stage those documents that have status equal to "A".

Second Stage: The $group stage groups the documents by the cust_id field to calculate the sum of the amount for each unique cust_id.
    -The MongoDB aggregation pipeline consists of stages. Each stage transforms the documents as they pass through the pipeline. Pipeline stages do not need to produce one output document for every input document; e.g., some stages may generate new documents or filter out documents.
Aggregations by Example