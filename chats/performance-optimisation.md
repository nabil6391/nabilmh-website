# Performance Optimisation

**Chat:** https://claude.ai/chat/0682e8c6-9de6-4561-a4a5-cbe171fddff1
**Status:** Draft

## Notes

Covers optimisation work across projects:
- Photo picker: 4s → 150ms (Kotlin coroutines, IO threading, lazy batch loading)
- App size: 21MB → 4MB (ProGuard)
- Home screen: 25% load improvement (Jobstreet)
- OPUS → CAF audio converter (bandwidth savings for Apple ecosystem)
- SQLite FTS for Quran full-text search
- Needleman-Wunsch for word-level audio alignment
