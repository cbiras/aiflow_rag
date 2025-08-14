# Evaluation Rubric & Targets

## Answer Quality (per question)
- **A (Good)**: Correct, grounded, cites relevant Item(s) (e.g., Item 7 or 1A) and includes a short quote or figure/unit. Concise (3–7 sentences).
- **B (Partial)**: Mostly correct but missing detail or weak/missing citation, or minor inaccuracies.
- **F (Fail)**: Incorrect, ungrounded, or contradictory to filing content.

## Retrieval Target
- For ≥80% of questions, at least one retrieved chunk in top-k (k=6) originates from the correct Item section typically containing the answer (e.g., Item 1, 1A, 7, 7A).

## Latency Targets (local dev)
- Retrieval: ≤ 1.0s
- Full inference (retrieval + LLM answer): ≤ 8–12s

## Cost Target
- ≤ $0.05 per query (baseline small model); we’ll log tokens to verify.
