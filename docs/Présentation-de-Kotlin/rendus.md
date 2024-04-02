---
layout: default
chapitre: Présentation de Kotlin
order: 2
---

# Présentation de Kotlin

```kotlin
fun main(){
    var nom = "fouad"
    var bonjour_nom = bonjour(nom)
    println (bonjour_nom)
    println (nom)
    }
    
    fun bonjour(nom:String):String{
    nom = "bonjour" + nom
    return nom
    }
    
```