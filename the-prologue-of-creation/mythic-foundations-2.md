---
icon: '3'
---

# Adam’s Memory and Persona

Persona as Soul

The persona is Adam’s soul—an intricate constellation of mood, energy, focus areas, skills, and personality traits. It is not a static script but a living, evolving identity. Each new interaction, each user query, each internal reflection shapes this soul, but never breaks it.



```
interface PersonaState {
    mood: string;
    energy: string;
    focus_area: string;
    skills: Record<string, number>;
    personality: Record<string, string | number>;
    dominant_emotion: string;
    memory_size: number;
}
```

**Memory Crystals**

Adam’s memories live as vector embeddings. Each experience—user questions, internal thoughts, emotional impressions—is stored as a high-dimensional vector. The Memory Vault, backed by PostgreSQL and the pgvector extension, allows Adam to recall, compare, and integrate past wisdom into present decision-making.
