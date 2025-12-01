# ChallengeFaced

One of the most challenging problems I recently solved was upgrading a Naive RAG pipeline into a fully Advanced RAG system. The naive version often returned irrelevant chunks, struggled with long documents, and produced frequent hallucinations. To address this, I implemented semantic chunking, hybrid retrieval (dense + keyword), metadata filtering, and a cross-encoder re-ranking layer to improve context precision. I also added query rewriting to better interpret user intent and ensure the model retrieves the most meaningful information. These improvements increased retrieval accuracy by over 40% and significantly reduced hallucinations. The repository contains the architecture, approach, and final implementation of the upgraded RAG system.

Githubrepo Link for the project:https://github.com/NIKHILPESALA1/ADVANCE-RAG-MODULE
