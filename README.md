# Design

The Adapter Pattern acts as an intermediate between two components, that cannot interact with each other directly. There is no other reason to do this. For example, a legacy code or a third-party component that needs to be integrated with your new implementations will require such a pattern to be used.

The purpose of a Bridge Pattern is to provide different implementations and each of these implementations can be used in various ways. This is done using the abstract components. For examle, send an SMS or email notification to a user and send them in various ways like using web-service or third-party tools.

The purpose of the Mediator Pattern is to manage the complexity of the system by handling how they interact with each other. Otherwise, each of these classes will have references to the other classes in order to interact, when required. This would result in a spider web type system classes. So this can be avoided by using the Mediator Pattern.
