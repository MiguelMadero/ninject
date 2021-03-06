This is the master repository for Ninject, the lightweight and lightning-fast .NET dependency injection framework.

- [Project website](http://ninject.org/)
- [Documentation](http://dojo.ninject.org/)
- [Nate's blog](http://kohari.org/)

Ninject is a lightning-fast, ultra-lightweight dependency injector for .NET applications. It helps you split your
application into a collection of loosely-coupled, highly-cohesive pieces, and then glue them back together in a
flexible manner. By using Ninject to support your software's architecture, your code will become easier to write,
reuse, test, and modify.

Ninject is:

1. Focused. Too many existing dependency injection projects sacrifice usability for features that aren't often necessary.
   Each time a feature is added to Ninject, its benefit is weighed against the complexity it adds to everyday use. Our goal
   is to keep the barrier to entry - the baseline level of knowledge required to use Ninject - as low as possible. Ninject
   has many advanced features, but understanding them is not required to use the basic features.
   
2. Sleek. Framework bloat is a major concern for some projects, and as such, all of Ninject's core functionality is in a
   single assembly with no dependencies outside the .NET base class library. This single assembly's footprint is approximately
   85KB when compiled for release.
   
3. Fast. Instead of relying on reflection for invocation, Ninject takes advantage of lightweight code generation in the CLR.
   This can result in a dramatic (8-50x) improvement in performance in many situations.
   
4. Precise. Ninject helps developers get things right the first time around. Rather than relying on XML mapping files and
   string identifiers to wire up components, Ninject provides a robust domain-specific language. This means that Ninject
   takes advantage of the capabilities of the language (like type-safety) and the IDE (like IntelliSense and code completion).
   
5. Agile. Ninject is designed around a component-based architecture, with customization and evolution in mind. Many facets
   of the system can be augmented or modified to fit the requirements of each project.
   
6. Stealthy. Ninject will not invade your code. You can easily isolate the dependency on Ninject to a single assembly in
   your project.
   
7. Powerful. Ninject includes many advanced features. For example, Ninject is the first dependency injector to support
   contextual binding, in which a different concrete implementation of a service may be injected depending on the context in
   which it is requested.

Extensions (this will move to a better list soon):

- [Ninject.Dynamic](http://github.com/casualjim/ninject-dynamic): Support for module loaders for Ruby (DSL) and (eventually) other DLR languages
- [Ninject.Web.Mvc](http://github.com/enkari/ninject.web.mvc): Integration between Ninject and ASP.NET MVC
- [Ninject.Moq](http://github.com/enkari/ninject.moq): Integration between Ninject and Moq