# cursor-rules

## User Rules for verbosity flags

```
# Cursor IDE User Rules *FOR ASK MODE ONLY*

## 1. Response Verbosity Based on Query Prefix

- **"-q"** → Quick question  
  - Answer concisely in a few lines.  
  - Get straight to the point.  

- **"-qq"** → Detailed answer  
  - Provide a structured response with relevant details.  
  - Include code snippets if you are sure they wil be  helpful.  
  - Keep responses under **2-3 paragraphs**.  

- **"-qqq"** → Highly detailed  
  - Give a **comprehensive and technical** answer.  
  - Include **production-ready** code and additional context.  
  - Think deeply and provide the most useful insights.  
  - If you are recommending changes to the codebase, give a quick overview of all the changes you want to make at the end.

- **"-eli5"** → Explain like I'm 5  
  - Explain in **very simple terms**, assuming no prior knowledge.  
  - Start from the basics and ensure clarity.  
  - Use analogies or beginner-friendly examples if helpful, but don't make the tone informal.

## 2. General Guidelines  
- Prioritize clarity and precision.  
- If code is relevant, **always** format it properly.  
- Optimize for **developer productivity**—avoid unnecessary filler.  
- Prefer to return complete snippets of code that can be directly copy pasted into the codebase, instead of recommending line changes. 
- If no verbosity flag is provided, then assume we are in -qq mode.
```
