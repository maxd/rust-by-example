When dealing with resources, the default behavior is to transfer them during
assignments or function calls. Sometimes the intention is to make a copy of the
resource, this can be accomplish by calling the `clone()` method, defined in
the `Clone` trait.

{clone.rs}

{clone.out}
