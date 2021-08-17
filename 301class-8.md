## [API Design Best Practices](https://docs.microsoft.com/en-us/azure/architecture/best-practices/api-design)

**1-What does REST stand for?**

Representational State Transfer

**2-What does REST stand for?**

Resource like object , data , services.

**3-What is an identifer of a resource? Give an example.**

the identifier is the URI that specifically and uniquely defines a resouce.
[https://example.com/*](https://example.com/*)

**4-What are the most common HTTP verbs?**

GET,POST,PUT,DELETE,PATCH



**5-What should the URIs be based on?**

should be based on nouns and verbs

**6-Give an example of a good URI.**

[https://example-site.com/orders](https://example-site.com/orders)

**7-What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

chatty implies there are multiple requests , each gathering small bits of data. this is poor practice as a large scales, this can tie up resources. better design would be to have fewer requests that recieve bigger allotments of data.

**8-What status code does a successful GET request return?**

A 200 (ok) code.

**9-What status code does an unsuccessful GET request return?**
404 error 

**10-What status code does a successful POST request return?**

201 CHEATED code 

**11-What status code does a successful DELETE request return?**
204 NO CONTENT code 


## [Framework vs library vs package vs module: The debate](https://medium.com/ieee-ensias-student-branch/framework-vs-library-vs-package-vs-module-the-debate-e1013a3e114d)

**Module**

Is the smallest piece of software. A module is a set of methods or functions ready to be used somewhere else.

**Package**

Is a collection of modules. This may sound funny, but usually what a package does, is gather a number of modules holding in general the same functional purpose. Making it easier to include all the related modules at once.

**Library**

Well library at it’s core, is a collections of packages. It’s purpose is to offer a set of functionalities ready to use without worrying about the subsequent packages.

**Framework**

It’s a set of libraries. But this time, the framework does not just offer functionalities, but it also provides an architecture for the development work. In other words you don’t include a framework.