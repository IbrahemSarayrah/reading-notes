# Readings: AWS: API, Dynamo and Lambda

* Amazon DynamoDB is a key-value and document database that delivers single-digit millisecond performance at any scale. It's a fully managed, multi-region, multi-active, durable database with built-in security, backup and restore, and in-memory caching for internet-scale applications. DynamoDB can handle more than 10 trillion requests per day and can support peaks of more than 20 million requests per second.

## What are serverless functions?

* serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies. The engineering teams within those companies ensure that the serverless functions have near-perfect uptime, redundant instances around the world, and scale to any incoming network request volume.

## If you were to create a system that emulated Lambda functions, how would you do it?

* using the Lambda console to create a Node.js Lambda function

* To create a Lambda function with the console
>
> 1. Open the Functions page on the Lambda console.
>
> 2. Choose Create function.
>
> 3. Under Basic information, do the following:
>
> * For Function name, enter my-function.
> * For Runtime, confirm that Node.js 14.x is selected. Note that Lambda provides runtimes for .NET (PowerShell, C#), Go, Java, Node.js, Python, and Ruby.
>
> * Choose Create function.
>

## Describe how a CDN works

* To minimize the distance between the visitors and your website’s server, a CDN stores a cached version of its content in multiple geographical locations (a.k.a., points of presence, or PoPs). Each PoP contains a number of caching servers responsible for content delivery to visitors within its proximity.

* CDN puts your content in many places at once, providing superior coverage to your users. For example, when someone in London accesses your US-hosted website, it is done through a local UK PoP. This is much quicker than having the visitor’s requests, and your responses, travel the full width of the Atlantic and back.

* CDN Building Blocks :
>
> CDN PoPs (Points of Presence) are strategically located data centers responsible for communicating with users in their geographic vicinity. Their main function is to reduce round trip time by bringing the content closer to the website’s visitor. Each CDN PoP typically contains numerous caching servers.
>
> Caching servers are responsible for the storage and delivery of cached files. Their main function is to accelerate website load times and reduce bandwidth consumption. Each CDN caching server typically holds multiple storage drives and high amounts of RAM resources.
>
> Inside CDN caching servers, cached files are stored on solid-state and hard-disk drives (SSD and HDD) or in random-access memory (RAM), with the more commonly-used files hosted on the more speedy mediums. Being the fastest of the three, RAM is typically used to store the most frequently-accessed items.
>

## Document the following Vocabulary Terms

* Serverless Functions: serverless functions are single-purpose, programmatic functions that are hosted on managed infrastructure. These functions, which are invoked through the Internet, are hosted and maintained by cloud computing companies.

* Cloud Storage: Cloud storage is a cloud computing model that stores data on the Internet through a cloud computing provider who manages and operates data storage as a service. It’s delivered on demand with just-in-time capacity and costs, and eliminates buying and managing your own data storage infrastructure. This gives you agility, global scale and durability, with “anytime, anywhere” data access.

* CDN: it is a set of linked servers which accelerate giving the data (photo, video, scripts) back to the user. CDN servers are placed as close as possible to the end audience.
