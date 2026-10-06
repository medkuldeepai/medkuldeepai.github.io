---
title: "AI Voice Assistant"
date: 2026-08-24
---

# AI Voice Assistant


A fully local, GPU-accelerated AI voice assistant designed for low-latency, natural voice conversations.

The project combines Voice Activity Detection (VAD), speech recognition, a local Large Language Model, streaming text generation, neural text-to-speech, conversational memory, and interruptible speech (barge-in) into a single real-time pipeline.

The assistant runs locally on an NVIDIA RTX 5060 Laptop GPU with 8 GB VRAM, using Faster-Whisper for speech recognition, Qwen3 8B through Ollama for language generation, and Kokoro for neural text-to-speech. The system is designed to minimize latency while keeping the entire conversation local.


<h2>System Architecture</h2>

<div style="text-align:center; margin:20px 0;">
  <img src="/images/ai-voice-assistant.png"
       alt="AI Voice Assistant Architecture"
       style="max-width:100%; border-radius:10px;">
</div>

<p style="text-align:center;">
  Architecture of the local AI voice assistant showing the complete real-time speech pipeline.
</p>

## Learn / Watch

YouTube: Full Project Explanation & Tutorial

GitHub: Complete Source Code

A live demonstration can also be provided from my local development machine.

## Requirements 
NVIDIA GPU with CUDA support.


Minimum 8 GB VRAM recommended for the current configuration.

