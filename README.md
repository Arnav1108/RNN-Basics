# Basic LSTM Implementation

## Overview
This repository contains a **basic LSTM (Long Short-Term Memory) implementation** using a **very small dataset**.  
The goal is **not performance**, **not accuracy**, and definitely **not production**.

The sole purpose is to:
- Understand how LSTMs process sequences
- See how memory (cell state) and gates actually work
- Build intuition before jumping into large models or Transformers
---

## Dataset
- Extremely small sequence-based data (course handout of a proffesor)
- No real-world complexity
- Chosen intentionally for **clarity**, not realism

Example use cases:
- Character-level prediction
- Simple sequence forecasting
- Toy text or numeric sequences

---

## Model Architecture
- Embedding layer (optional, depending on task)
- Single LSTM layer
- Fully connected output layer

No stacking. No tricks. No overengineering.

---

## Key Concepts Demonstrated
- Sequential input processing
- Hidden state vs cell state
- Effect of sequence length
- Why LSTMs handle long-term dependencies better than vanilla RNNs
- How gradients flow throu
