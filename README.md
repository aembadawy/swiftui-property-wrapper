# swiftui-property-wrapper

SwiftUI offers 17 property wrappers for our applications, each of which provide different functionality. Knowing which one to use and when is critical to getting things right.

## @State Property Wrapper

In SwiftUI views or a function of state **f(s) = V**  which means any time we want to modify our review or change any functionality or the way it looks, we need to introduce a *@State* property.

**@State** is a property wrapper used to create and manage mutable state within a view. It's a fundamental concept that allows you to store and track changes to a value so that your view can automatically update whenever that value changes.
**@State** is used primarily for managing small amounts of mutable data that are specific to a single view.

*And how it works is essentially SwiftUI discords the previous view and redraws a new view whenever any change occurs in a state variable.*

## @Binding Property Wrapper

In SwiftUI, @Binding is a property wrapper used for creating a two-way connection between a property's value in one view and its| value in another view or a parent view. It's typically used to pass data between views and synchronize changes bidirectionally.

**@Binding** creates a link to a @State property. We cannot create @Binding without @State.
@State property is the origin. Modifying @Binding modifies original @State.

## @Published Property Wrapper


