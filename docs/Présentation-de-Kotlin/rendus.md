---
layout: default
chapitre: Présentation de Kotlin
order: 2
---

# Présentation de Kotlin

```bash
fun main() {
    println("Hello, world!")
}
```
```bash
Hello, world!
```
<!-- new slide -->

## Examples

```bash
fun main() {
    val count : Int = 2
    println(count)
}
```
```bash

fun main() {
    val count: Int = 2
    println("You have $count unread messages.")
}

```
```bash
fun main() {
    birthdayGreeting()
    println(birthdayGreeting())
}
```
```bash
fun birthdayGreeting(): String {
    val nameGreeting = "Happy Birthday, Rover!"
    val ageGreeting = "You are now 5 years old!"
    return "$nameGreeting\n$ageGreeting"
}
```
```bash
fun main() {
    birthdayGreeting()
}
```
```bash
fun birthdayGreeting(): Unit {
    println("Happy Birthday, Rover!")
    println("You are now 5 years old!")
}
```
```bash
fun main() {
    birthdayGreeting("Ahmed")
    println(birthdayGreeting("Ahmed"))
}
```
```bash
fun birthdayGreeting(name: String): String {
    val nameGreeting = "Happy Birthday, $name!"
    val ageGreeting = "You are now 5 years old!"
    return "$nameGreeting\n$ageGreeting"
}
```
```bash
fun main() {
    birthdayGreeting("Ahmed",24)
    println(birthdayGreeting("Ahmed",24))
}
```
```bash
fun birthdayGreeting(name: String, age: Int): String {
    val nameGreeting = "Happy Birthday, $name!"
    val ageGreeting = "You are now $age years old!"
    return "$nameGreeting\n$ageGreeting"
}
```
