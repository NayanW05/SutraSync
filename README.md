# SutraSync

### Learn Offline. Submit Once. Never Lose the Attempt.

## About the Project
SutraSync is a proposed offline-first learning and assessment platform designed to help students complete online assessments even when internet connectivity is unstable.

Students can download quizzes, attempt them offline, automatically save their answers and synchronize submissions when connectivity is restored.

## Problem Statement
Unstable internet connections can interrupt online assessments, resulting in lost answers, uncertain submission status and duplicate attempts.

## Key Features
- Offline Quiz Access
- Automatic Answer Saving
- Reliable Submission Synchronization
- Duplicate Submission Prevention
- Quiz Version Protection
- Teacher Dashboard

## Proposed Technology Stack
- Frontend: React, TypeScript, Vite
- Local Storage: IndexedDB, Dexie
- Offline Support: PWA, Service Worker
- Backend: Python, FastAPI
- Database: PostgreSQL
- Authentication: JWT / Supabase Auth

## How It Works
1. Student downloads a quiz.
2. Student attempts the quiz offline.
3. Answers are automatically saved locally.
4. Submission is stored in a pending queue.
5. When connectivity returns, the submission is synchronized.
6. The server verifies the attempt and returns a durable receipt.

## Project Status
Currently at the proposal and design stage. Prototype implementation is planned as part of the hackathon.

## Team
Team Name: Invictus
