# Complex Systems Knowledge Base

A markdown-based knowledge base on complex systems, extracted from [Juanje Ojeda's blog](https://blog.juanjeojeda.com/) (Spanish) and translated into English.

## What is this

A set of interconnected wiki pages covering complex adaptive systems: emergence, attractors, feedback, adaptation, resilience, embodied cognition, agent dynamics, and more. Each page is atomic, densely linked, and structured with frontmatter, key points, examples, and connections.

Built using [Claude Code](https://claude.com/claude-code) and the [wiki-kb skill](https://gitlab.com/juanjeojeda/wiki-kb).

## How to use it

### Browse in Obsidian

Open the `wiki/` folder as an Obsidian vault. The internal links and graph view make it easy to navigate and discover connections.

### Query with Claude Code or Cursor

The `CLAUDE.md` file configures the AI assistant to answer questions using **only** the wiki content — a lightweight RAG approach without a vector database. The assistant navigates the wiki's internal links progressively instead of relying on keyword search.

```bash
cd blogs-kb
claude
# then ask: "What is the edge of chaos?"
# or: "What's the different between complicated, hard and complex problems?"
# or: "Is the back pain a complicated or a complex problem?"
# or: "What relationshipt there is between learning and adaptation?"
# ...
```

