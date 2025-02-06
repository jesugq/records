
Classes can be organized into logical groupings which are called packages. You declare a package name in the class using the package statement. If you don't declare a package, the class implicitly belongs to the default package.

A class is said to be a top-level class if it is defined in the source code file and not enclosed in the code block of another class, type, or method. A top-level class only has two valid access modifier options, public, or none.

- Public means any other class in any package can access this class.
- When the modifier is omitted, this has special meaning, called package access, meaning the class is accessible only to classes in the same package.

An access modifier at the member level allows granular control over class members. The valid access modifiers, from least restrictive to most restrictive are:

- Public means any other class in ay package can access this member.
- Protected allows classes in the same package, and any subclasses in other packages, to have access to the member.
- When the modifier is omitted, this has special meaning, called package access, meaning the member is accessible only to classes in the same package.
- Private means that no other class can access this member.

---

What the protected modifier says is, let any class that is a subclass access this field. This is conditional encapsulation. We're allowing some limited access to our internal fields, and that's to subclasses.

Protected access also means that any classes in the same package will also have access.
