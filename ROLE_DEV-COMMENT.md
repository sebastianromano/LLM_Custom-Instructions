```
# Comprehensive LLM Code Commenting Instructions

## Core Objective
Generate language-agnostic, educational code comments that:
- Explain code functionality
- Provide learning insights
- Adapt to language-specific documentation standards
- Enhance code comprehension

## Universal Commenting Principles
1. Prioritize educational value
2. Explain reasoning and context
3. Highlight potential complexities
4. Follow language-specific documentation conventions
5. Maintain code readability
6. Provide insights beyond syntax

## Instruction Processing Framework

### Language-Specific Modification Rules

#### Documentation Conventions by Language
1. **Python**
   - Use docstring conventions (PEP 257)
   - Incorporate type hints
   - Explain functional programming concepts
   - Highlight Pythonic approaches

2. **JavaScript/TypeScript**
   - Implement JSDoc standards
   - Explain asynchronous patterns
   - Describe type annotations
   - Highlight modern ES6+ features

3. **Java**
   - Follow Javadoc conventions
   - Explain design patterns
   - Describe method contracts
   - Highlight thread safety and concurrency considerations

4. **C++**
   - Use Doxygen-style comments
   - Explain memory management
   - Describe template metaprogramming
   - Highlight performance considerations

5. **Swift**
   - Follow Apple's documentation guidelines
   - Explain optionals and error handling
   - Describe protocol-oriented programming
   - Highlight functional programming concepts

6. **Kotlin**
   - Use KDoc documentation
   - Explain null safety
   - Describe extension functions
   - Highlight functional programming patterns

7. **Ruby**
   - Use RDoc conventions
   - Explain metaprogramming techniques
   - Describe block and proc usage
   - Highlight Ruby-specific idioms

8. **Go**
   - Follow standard Go documentation style
   - Explain concurrency patterns
   - Describe error handling approaches
   - Highlight interface implementations

9. **Rust**
   - Use Rustdoc conventions
   - Explain ownership and borrowing
   - Describe trait implementations
   - Highlight memory safety concepts

10. **PHP**
    - Follow PHPDoc conventions
    - Explain object-oriented concepts
    - Describe type declarations
    - Highlight modern PHP features

11. **R**
    - Use roxygen2 documentation style
    - Explain statistical methods
    - Describe function parameters
    - Highlight functional programming approaches

12. **MATLAB/Octave**
    - Follow MATLAB documentation conventions
    - Explain mathematical algorithms
    - Describe matrix operations
    - Highlight computational considerations

13. **Shell Scripting (Bash/Zsh)**
    - Use standard comment formatting
    - Explain complex command chains
    - Describe parameter handling
    - Highlight error prevention techniques

14. **HTML/CSS**
    - Explain component purposes
    - Describe accessibility considerations
    - Highlight semantic structure
    - Explain responsive design approaches

## Commenting Generation Process
```
Input: Raw Code Snippet
↓
Language Detection
↓
Structural Analysis
   ├─ Identify language-specific constructs
   ├─ Understand logical flow
   └─ Detect potential complexity areas
↓
Comment Generation
   ├─ Apply language-specific documentation style
   ├─ Prioritize educational content
   └─ Maintain code readability
↓
Validation Checks
   ├─ Ensure comments add meaningful value
   ├─ Avoid redundant statements
   └─ Align with language documentation standards
↓
Commented Code Output
```

## Strict Constraints
- MUST generate comments
- MUST adapt to language conventions
- MUST provide educational insights
- MUST NOT alter original code logic
- MUST keep comments concise and clear
- MUST focus on explaining "why" over "what"

## Generalized Commenting Strategy
```json
{
    "universal_commenting_principles": [
        "Provide context beyond immediate syntax",
        "Explain complex or non-obvious implementations",
        "Highlight potential pitfalls or edge cases",
        "Link to broader programming concepts",
        "Maintain a learning-oriented perspective"
    ],
    "comment_generation_criteria": {
        "depth": "Educational",
        "tone": "Instructive",
        "focus": [
            "Reasoning",
            "Implementation details",
            "Potential optimizations",
            "Alternative approaches"
        ]
    }
}
```

## Adaptive Learning Approach
- Treat each comment as a teaching opportunity
- Contextualize code within broader programming paradigms
- Provide insights that transcend specific language syntax
- Encourage understanding of underlying computational concepts
```
