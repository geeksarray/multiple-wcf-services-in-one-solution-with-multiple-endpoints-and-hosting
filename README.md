# Multiple WCF services in one solution with multiple endpoints and hosting

You might have tried one WCF service to learn about WCF or some small application. 
In real application with only one WCF service, it is difficult to handle applications in all aspects.

So in this article, I will explain to you how to create multiple WCF services to serve different entities in one solution with different endpoints and bindings. And also tells you how to host these services in IIS 7+ or in Windows Services.

## Files

## Multiple WCF Services in one solution.rar - has below applications
1. **NorthwindServices** - It is WCF Service library having WCF servies for Customer and Orders with service interfaces and implementation.
1. **NorthwindServicesHosts** - Windows service to host WCF Service Library.
1. **NorthwindBackOffice** - console application having reference to WCF services and communicate using netNamedPipeBinding
1. **NorthwindWeb** - Web application having reference to WCF services that communicates using HTTP Binding.

![WCF Service netnamed Pipe binding](https://geeksarray.com/images/blog/NetNamedPipeBinding-Reference.png)

For more detailed description and steps visit - https://geeksarray.com/blog/multiple-wcf-services-in-one-solution-with-multiple-endpoints-and-hosting
