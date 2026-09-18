# Mission Reflection

Object storage is much better suited for storing millions of photos compared to a traditional block storage hard drive because it is designed for massive scalability. Block storage is limited by the size of the disk and is usually attached to only one server. Object storage, on the other hand, can store an almost unlimited number of files and is accessed through the internet using unique object IDs. This makes it perfect for applications that need to handle large volumes of user-uploaded images.

Using Docker made deploying the MinIO storage server much easier. Instead of installing and configuring MinIO manually on the server, I only needed to run a single Docker command. Docker automatically downloaded the image, set up the environment variables, and started the service. It also made the process consistent and easy to repeat.

A "bucket" in cloud storage is like a container or folder that holds objects (files). In MinIO and services like Amazon S3, buckets are used to organize and manage stored data. Each bucket has a unique name and can contain many objects.

Large enterprise companies protect their object storage data from physical server crashes by using replication and redundancy. They usually store multiple copies of the data across different servers and even different geographic locations (availability zones or regions). This way, if one server or even an entire data center fails, the data can still be accessed from another location.

My confidence in navigating the Linux command line is growing. At first, I was nervous about typing long Docker commands, but after practicing and successfully deploying MinIO, I feel more comfortable. I am starting to understand how to check running containers, use environment variables, and troubleshoot basic issues. I still need more practice, but I can see clear improvement compared to the previous laboratories.
