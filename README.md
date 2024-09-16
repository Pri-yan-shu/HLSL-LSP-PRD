# HLSL LANGUAGE SERVER


## Summary

Language servers facilitate code editing by providing features such as autocomplete, error/warning detection.
Any editor providing support for LSP (Language server protocol) can use language server to allow these features for the language.
At the time of writing, there is no language server for HLSL (High Level Shader Language), which is used to write programs for GPU for Microsoft's Direct3D api's.
Only editor/IDE specific plugins exits, so there is no support for people using other editors (helix users, anyone?).

How LSP works: ![LSP](./language-server-sequence.png)


## Project Features (MVP)

HLSL language server will provide following features:

- Code Completion / Autosuggestion
- Goto Definition
- Hover to see documentation
- Code formatting
- Refactoring (Renaming)

## Suggested features (Not MVP)

- Warnings and Suggestions based on performance and branching of the program, providing branchless/optimised code when possible.
- Further refactoring (extract to method definition, extract expression to variable).


## Technical Requirements

### Tech stack
- Language Server Protocol
- JSON RPC
- Programming language
	

## Timeline

- End of this week: Hook up dummy server with editors
- By sept end: Discuss project scope/workflow, get started
- 1st week Oct: AST based syntax highlighting
- Oct end: ??? 
