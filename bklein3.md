
I am Ben Klein

# Ben Klein (robobenklein)

Graduate student focused on developer productivity and human computer interaction. Long history of software development on Linux, git, python, etc, for all reasons including personal projects, work, school, and just for fun.

## Project Idea

https://github.com/utk-se/WorldSyntaxTree

World Syntax Tree is a project to allow language-agnostic graph-based queries across as many codebases as possible.

It can be used for a variety of applications, imagine being able to ask any of these questions across all repositories and languages:

- Locate nested loops, classes, functions, and other complex code structures
- Locate the same algorithm implementation across different languages
- Resolve imports/includes using their local or aliased name, and automatically generate example real-world usages for libraries
- See how code changes by syntactic structure, rather than by lines
- Identify logical / flow changes between commits
- Follow the copy/paste/move of entire functions between files instead of looking like simple addition/deletion of lines

And many more!

Right now only the infrastructure part of the project is working, what's needed is an interface that allows users to write and visualize these kinds of queries effectively, most likely a web UI.

If you've ever used Neo4j you might have an idea of the interface we'd like to emulate. If not, there are some example WST query results used as the background of my post at https://unhexium.net/research/neo4j-performance-adventures-for-petabyte-scale-datasets/ and they look cool, right?

