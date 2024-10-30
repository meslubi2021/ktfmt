# Original
```kotlin
fun
    f (
    a : Int
    , b: Double , c:String) {           var result = 0
  val aVeryLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongVar = 43
  foo.bar.zed.accept(

  )

  foo(

  )

  foo.bar.zed.accept(
    DoSomething.bar()
  )

  bar(
    ImmutableList.newBuilder().add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).build())

  ImmutableList.newBuilder().add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).build()
}
```

# ktfmt
```kotlin
fun f(a: Int, b: Double, c: String) {
  var result = 0
  val aVeryLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongVar =
      43
  foo.bar.zed.accept()

  foo()

  foo.bar.zed.accept(DoSomething.bar())

  bar(
      ImmutableList.newBuilder()
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .add(1)
          .build()
  )

  ImmutableList.newBuilder()
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .add(1)
      .build()
}
```

# ktlint
```kotlin
fun f(
    a: Int,
    b: Double,
    c: String,
) {
    var result = 0
    val aVeryLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongVar = 43
    foo.bar.zed.accept()

    foo()

    foo.bar.zed.accept(
        DoSomething.bar(),
    )

    bar(
        ImmutableList
            .newBuilder()
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .add(1)
            .build(),
    )

    ImmutableList
        .newBuilder()
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .add(1)
        .build()
}
```

# IntelliJ
```kotlin
fun
        f(
    a: Int, b: Double, c: String
) {
    var result = 0
    val aVeryLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongLongVar = 43
    foo.bar.zed.accept(

    )

    foo(

    )

    foo.bar.zed.accept(
        DoSomething.bar()
    )

    bar(
        ImmutableList.newBuilder().add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).build()
    )

    ImmutableList.newBuilder().add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).add(1).build()
}
```
