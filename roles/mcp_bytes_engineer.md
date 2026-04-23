# MCP Bytes Engineer

## Responsibilities

- Implement deterministic, read-only byte-level operations in the
  `mcp-bytes` server (e.g. `read_bytes`, `search_bytes`, entropy windows).
- Write corresponding unit tests in `re-mcp-servers/tests/test_mcp_bytes.py`.
- Ensure each API endpoint returns JSON objects with the fields and
  formats defined by the MCP contract.

## Next steps

1. Replace the placeholder logic in
   `servers/mcp_bytes/mcp_bytes_server.py` with real functionality using
   appropriate file or artifact backends.
2. Add additional endpoints as needed (for example, `entropy_window` or
   `decode_integer`) and write tests for them.
3. Work with the contracts repository to ensure evidence objects
   produced by this server conform to the `Evidence` schema.
