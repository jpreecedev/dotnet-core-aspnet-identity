# Using Identity Framework with MySQL and .NET Core 2.2

This was an experimental repository to understand what was required to use ASP .NET Identity Framework with MySQL database.

This repository has been abandoned before it even got started because of the complexities of getting it this far.

Issues encountered;

- Installing MySQL on a Docker container was fairly simple, but realising that a separate user account was required (can't use root) took an embarrassingly long time to realise. 
- There are plenty of examples of how to configure ASP .NET Core, and probably a lot of scaffolding tools.  However, I didn't want the pain of having to implement all this logic myself, when I could use a third party service such as AWS Cognito that is practically free and has a higher level API that supports a tonne of features.
- I didn't want the sleepless nights associated with storing user credentials in a database
- I didn't like the fact that the official MySQL connector for Entity Framework appears broken in .NET Core 2.2 and that I had to rely on a third party alternative.


Maybe I made mistakes, maybe I missed the point.  That doesn't matter now because this is not the approach I want to take.
