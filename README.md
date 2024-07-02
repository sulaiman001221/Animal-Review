# Animal-Review

 Nest methods tests under class tests. For example.
```
describe("Dog Class", () => 
  describe("eat() method", () => {
    it("should ..........)
    });
  });
```
 Make your messages a bit more specific. For example.
`should return "Rax eats" when a Dog instance is created without a name`
`should return "Scooby eats"  when a Dog instance is created with the name "Scooby"`
You get the idea? keep it going.

 Make use of the "before each" function, to avoid re-initializing the same thing under each block. If you don't know about it, take some time to do research about it.
