# CFA RAG Learning Assistant demo based on Dify

This workspace contains a minimal Dify + Gemini API demo package for a CFA RAG learning assistant.

## Product Goal

Build a CFA study assistant that answers concept questions from a self-built knowledge base, explains exam relevance, warns about common traps, and suggests what to review next.

## MVP Stack

| Module | Tool |
| --- | --- |
| Frontend / workflow | Dify |
| LLM | Gemini 2.5 Flash or Gemini 2.5 Flash Lite |
| Knowledge base | Self-written CFA notes in `cfa_notes/` |
| Embedding | Dify default embedding or Gemini embedding |
| Wrong question log | `data/wrong_question_log.csv` |
| Evaluation set | `eval/cfa_rag_eval_30.csv` |
| Answer format | Fixed structured template |

## Folder Structure

```text
cfa_notes/                 # 10 knowledge base documents for Dify import
data/wrong_question_log.csv # Starter wrong-question tracking table
eval/cfa_rag_eval_30.csv    # 30 test questions for manual evaluation
prompts/dify_system_prompt.md
```

## Dify Setup

1. Create a Dify knowledge base.
2. Upload all Markdown files from `cfa_notes/`.
3. Connect Gemini API and choose Gemini 2.5 Flash or Flash Lite.
4. Use `prompts/dify_system_prompt.md` as the app instruction.
5. Test with the questions in `eval/cfa_rag_eval_30.csv`.

## Required Answer Format

```text
Core Concept:
Exam Relevance:
Formula / Logic:
Common Trap:
Mini Example:
What to Review Next:
Source:
Confidence:
```

## Privacy Note

Do not upload company documents, client data, or sensitive materials to a free-tier prototype. Use self-written notes or public-domain learning material only.
