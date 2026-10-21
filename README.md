# OWNEX Voice Assistant

## Voice Chat Integration

The voice and written chat channel follows the same protocol:

```bash
# Health check via voice
orion doctor

# Status check
orion status

# Both follow the same working state - verified operational
```

## Protocol

Both voice (chat de voz) and written chat follow identical health verification:

- `/api/health` endpoint
- `/api/system/health` endpoint
- `/api/system/status` endpoint

All three return consistent status across modalities.

## Current State

Voice and written channels are confirmed working perfectly with full feature parity.
