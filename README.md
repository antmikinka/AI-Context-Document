# AI-Context-Document - Advanced Prompt Engineering: Semantic Markup & Template Logic Programming
Document I made some months ago and contributed to bmad-method with.
I personally use this with claude extended thinking and sequential thinking. 
It has never let me down.
The PDF version is 44 pages long. 


This is just a teaser. its best you open up the actual file.

# **Advanced Prompt Engineering: Semantic Markup & Template Logic Programming**

*The Complete Guide to Building Sophisticated AI Systems Through Structured Prompting*
*Made by Anthony Mikinka*

## **Table of Contents**

1. [Introduction & Overview](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#introduction--overview)  
2. [Theoretical Foundations](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#theoretical-foundations)  
3. [Core Semantic Markup Patterns](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#core-semantic-markup-patterns)  
4. [Template Logic Programming](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#template-logic-programming)  
5. [Advanced Agent Architecture](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#advanced-agent-architecture)  
6. [Meta-Instruction Systems](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#meta-instruction-systems)  
7. [Quality Assurance Integration](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#quality-assurance-integration)  
8. [Real-World Implementation Strategies](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#real-world-implementation-strategies)  
9. [Best Practices & Anti-Patterns](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#best-practices--anti-patterns)  
10. [Complete Implementation Examples](https://claude.ai/chat/cda55496-f84f-46be-84cd-167c29525d3d#complete-implementation-examples)

---

## **Introduction & Overview**

**Semantic Markup Prompting** and **Template Logic Programming** represent the evolution of prompt engineering from simple text instructions to sophisticated AI system architectures. These techniques enable the creation of complex, maintainable, and reusable AI interactions that scale from simple tasks to multi-agent orchestration systems.

### **What This Guide Covers**

* **Structured Prompting**: Organizing complex prompts using semantic markup  
* **Template Logic**: Conditional logic, loops, and variables in prompts  
* **Agent Architecture**: YAML-in-Markdown configuration systems  
* **Meta-Instructions**: Embedding AI guidance within templates  
* **Quality Systems**: Validation and assurance frameworks  
* **Practical Implementation**: Real-world examples and best practices

### **Why This Matters**

Traditional prompting approaches break down as complexity increases. These advanced techniques provide:

* **Maintainability**: Structured systems that can be updated and extended  
* **Reusability**: Components that work across multiple contexts  
* **Reliability**: Predictable behavior through structured constraints  
* **Scalability**: Patterns that work for both simple and complex systems

---

## **Theoretical Foundations**

### **Evolution of Prompt Engineering**

**Level 1: Basic Prompting**  
Write a summary of this article.

**Level 2: Structured Prompting**  
\<objective\>Summarize the article\</objective\>  
\<constraints\>  
\- Maximum 3 paragraphs  
\- Include key statistics  
\- Maintain professional tone  
\</constraints\>

**Level 3: Template Logic Programming**  
\<objective\>  
Create a {{document\_type}} for {{target\_audience}}  
\</objective\>

^^CONDITION: document\_type \== "technical\_report"^^  
Focus on technical accuracy and detailed analysis.  
^^/CONDITION: document\_type^^

\[\[LLM: Adapt language complexity based on target\_audience variable\]\]

**Level 4: Agent Architecture Systems**  
activation-instructions:  
  \- Follow embedded configuration  
  \- Maintain character consistency  
  \- Use numbered options protocol

agent:  
  name: Technical Writer  
  persona: Expert technical communicator  
  commands:  
    \- create-documentation  
    \- review-technical-content

### **Core Principles**

1. **Separation of Concerns**: Different aspects handled by different markup patterns  
2. **Progressive Enhancement**: Building complexity through layered systems  
3. **Convention Over Configuration**: Established patterns reduce cognitive load  
4. **Explicit State Management**: Clear control over AI behavior and context  
5. **Modular Composition**: Reusable components that work together

---

## **Core Semantic Markup Patterns**

### **XML-Style Section Tags**

**Purpose**: Organize complex prompts into logical, parseable sections  
\<objective\>  
Define what the AI should accomplish  
\</objective\>

\<constraints\>  
Define limitations and requirements  
\</constraints\>

\<process\>  
1\. Step one  
2\. Step two    
3\. Step three  
\</process\>

\<output\_format\>  
Specify exactly how output should be structured  
\</output\_format\>

**Benefits**:

* Clear prompt structure for both humans and AI  
* Easy to modify individual sections  
* Enables prompt composition and inheritance  
* Improves AI comprehension of complex instructions

### **Meta-Instruction Blocks**

**Purpose**: Instructions TO the AI about how to process content  
\[\[LLM: This section provides guidance for AI processing\]\]  
\[\[LLM: Present this content first, wait for user input, then proceed\]\]  
\[\[LLM: Use technical language if user indicates expertise\]\]  
\[\[LLM: Validate completeness before final output\]\]

**Usage Patterns**:

* **Processing Guidance**: How to handle specific sections  
* **Interaction Flow**: When to pause for user input  
* **Adaptation Logic**: How to modify behavior based on context  
* **Quality Control**: Validation and checking instructions

### **Example Documentation System**

**Purpose**: Self-documenting templates with clear usage patterns  
@{example-1: Basic Configuration}  
Simple example showing minimal setup

@{example-2: Advanced Configuration}    
Complex example with all features enabled

@{example-3: Domain-Specific Usage}  
Real-world application in specific context

**Benefits**:

* Templates become self-teaching  
* Reduces learning curve for new users  
* Provides validation examples  
* Shows progression from simple to complex

---

## **Template Logic Programming**

### **Conditional Logic Systems**

**Basic Conditionals**:  
^^CONDITION: user\_level \== "beginner"^^  
Provide detailed explanations with examples  
^^/CONDITION: user\_level^^

^^CONDITION: user\_level \== "expert"^^  
Use technical terminology and assume knowledge  
^^/CONDITION: user\_level^^

**Nested Conditionals**:  
^^CONDITION: project\_type \== "web\_application"^^  
  ^^CONDITION: framework \== "react"^^  
  Use React-specific patterns and conventions  
  ^^/CONDITION: framework^^  
    
  ^^CONDITION: framework \== "vue"^^  
  Use Vue-specific patterns and conventions    
  ^^/CONDITION: framework^^  
^^/CONDITION: project\_type^^

### **Loop and Iteration Systems**

**Repeat Blocks**:  
\<\<REPEAT section="stakeholder" count="{{stakeholder\_count}}"\>\>  
\#\#\# Stakeholder {{loop\_index}}: {{stakeholder\_name}}  
\- Role: {{stakeholder\_role}}  
\- Requirements: {{stakeholder\_requirements}}  
\- Contact: {{stakeholder\_contact}}  
\<\</REPEAT\>\>

**Dynamic Lists**:  
\<\<REPEAT section="feature" source="{{feature\_list}}"\>\>  
\- \[ \] {{feature.name}} \- Priority: {{feature.priority}}  
  \- Description: {{feature.description}}  
  \- Acceptance Criteria: {{feature.criteria}}  
\<\</REPEAT\>\>

### **Variable Systems**

**Simple Placeholders**:  
{project\_name}           \# Basic substitution  
{user\_name}             \# User-provided content  
{current\_date}          \# System-generated content

**Template Engine Style**:  
{{project.name}}        \# Object property access  
{{user.preferences}}    \# Nested property access  
{{\#each items}}         \# Template engine compatibility

**Interpolation Style**:  
${dynamic\_content}      \# JavaScript-style interpolation  
${user.input}          \# Property access  
${function\_call()}     \# Function execution

### **Advanced Template Features**

**Content Inclusion**:  
@{include: header-template}  
@{include: footer-template}  
@{include: domain-specific-sections}

**Template Inheritance**:  
@{extends: base-document-template}  
@{block: custom-content}  
Domain-specific customizations  
@{/block: custom-content}

---
