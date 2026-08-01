# TypeScript Notes - Day 95

## What is TypeScript?
- Superset of JavaScript with static typing
- Compiles to plain JavaScript
- Catches errors at compile time instead of runtime

## Basic Types
- string, number, boolean
- array: number[] or Array<number>
- tuple: [string, number]
- enum: enum Direction { Up, Down, Left, Right }
- any, void, null, undefined

## Interfaces
- Define the shape of an object
- interface User { name: string; age: number; }
- Can be extended with extends keyword

## Type Aliases
- type Point = { x: number; y: number }
- More flexible than interfaces for unions/intersections

## Generics
- Write reusable, type-safe functions
- function identity<T>(arg: T): T { return arg; }
