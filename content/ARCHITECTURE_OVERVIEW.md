# Architecture Overview

## Purpose

This local-only portfolio overview explains how the four flagship projects fit together as one safety-bounded dental AI workflow infrastructure stack.

## The Stack

### 1. Dental Case Packet / AI-ready Dental Data Layer

The Dental Case Packet is the data layer.

It organizes fragmented dental workflow context into source-grounded, provenance-aware, human-reviewable packets. It is synthetic-first and non-diagnostic.

### 2. Clinical AI Review Harness

The Clinical AI Review Harness is the safety evaluation layer.

It is paired with the subtitle `Workflow Safety Review Harness for Synthetic Drafts`. It checks synthetic drafts for boundary risk, unsupported inference, missing-information awareness, provenance issues, prohibited output patterns, and human-review routing.

### 3. AI Native Dental Phone Layer

The AI Native Dental Phone Layer is the dentist review workflow layer.

It models how non-final drafts can move through review states such as drafted, needs review, edited, approved for manual handling, rejected, or escalated.

### 4. Taiwan Dental Prep / 台灣安心看牙

Taiwan Dental Prep is the market validation use case.

It shows how the workflow infrastructure can support conservative appointment-preparation and document-organization needs without becoming a diagnosis, treatment recommendation, automatic second opinion, teledentistry service, or patient-facing medical advice system.

## Flow

`Dental Case Packet -> Clinical AI Review Harness -> Dentist-in-the-loop workflow -> Taiwan Dental Prep use case`

## Layer Summary

- Dental Case Packet: data layer.
- Clinical AI Review Harness: safety evaluation layer.
- AI Native Dental Phone Layer: dentist review workflow layer.
- Taiwan Dental Prep: market validation use case.

## Safety Boundary

No layer is described as clinical diagnosis, treatment recommendation, automatic second opinion, teledentistry, clinical validation, image interpretation, or patient-facing medical advice.

The stack is local-only, synthetic-first, provenance-aware, and human-in-the-loop.

