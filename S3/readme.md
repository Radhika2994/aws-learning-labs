While working with AWS, I also learned about Amazon S3 (Simple Storage Service).

S3 is basically like a giant online storage drive where we can keep any type of file — documents, images, videos, backups, etc.

The main difference from normal storage is that S3 is stored in AWS’s cloud.

This makes it highly durable (almost never loses data), available from anywhere, and easy to share.

Instead of storing files directly, S3 organizes them into Buckets.

Buckets are like folders, but in AWS they are the top-level container for storing data.

Each bucket has a unique name and can be accessed over the internet if permissions allow.

Inside a bucket, we can store unlimited files called objects.

While learning S3, I understood these important concepts:

Buckets

They are the main containers in S3 where all files are stored.

Each bucket exists in a specific AWS Region (e.g., us-east-1, ap-south-1).

Bucket names must be globally unique — no two people can have the same bucket name.

Objects

Every file in S3 is called an object.

Objects have two main parts: the data (the file itself) and metadata (extra info like file type, size, etc.).

Storage Classes
AWS S3 offers different storage types depending on how often we need the data and how much we want to pay:

S3 Standard: For frequently accessed data.

S3 Intelligent-Tiering: Automatically moves data between frequent and infrequent storage to save cost.

S3 Standard-IA (Infrequent Access): For files accessed less often but still need to be retrieved quickly.

S3 One Zone-IA: Cheaper but stores data in only one zone (less redundancy).

S3 Glacier: For archiving data that is rarely accessed (very cheap but takes hours to retrieve).

S3 Glacier Deep Archive: For long-term archival (cheapest, but retrieval is slow).

S3 Replication
S3 can automatically copy objects from one bucket to another.

This is useful for backup or storing data in multiple regions for disaster recovery.

Two main types:

CRR (Cross-Region Replication): Copies data to a bucket in a different region.

SRR (Same-Region Replication): Copies data to another bucket in the same region.

