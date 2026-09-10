<div align="center">

# Fongap

**AI infrastructure · local-first tools · self-hosted systems**

Building small, reliable systems around AI, automation, and personal computing.

[**Blog**](https://www.fongap.com) · [**AI Gateway**](https://github.com/fongap/ai-gateway) · [**Delta**](https://github.com/fongap/delta)

</div>

<br>

### Selected work

<table>
<tr>
<td width="50%" valign="top">

#### [ai-gateway](https://github.com/fongap/ai-gateway)

A resilient multi-provider AI gateway with smart routing, tiered failover and OpenAI / Anthropic-compatible APIs.

`TypeScript` · `Cloudflare Workers` · `LLM Routing`

</td>
<td width="50%" valign="top">

#### [delta](https://github.com/fongap/delta)

A local-first AI assistant for personal work, built around explicit execution, verifiable state and durable context.

`Python` · `Rust` · `Local-first`

</td>
</tr>

<tr>
<td width="50%" valign="top">

#### [server-edge](https://github.com/fongap/server-edge)

A modular service foundation for Linux hosts — from cloud instances to local machines.

`Linux` · `Docker` · `Self-hosted`

</td>
<td width="50%" valign="top">

#### [action-worker](https://github.com/fongap/action-worker)

A thin GitHub Actions execution layer that decouples orchestration from private build and deployment logic.

`GitHub Actions` · `Shell` · `CI/CD`

</td>
</tr>
</table>

<br>

### System

```text
Personal Work
     │
     ▼
   Delta
     │
     ▼
AI Gateway ──────► AI Providers

Server Edge ─────► Runtime & Services

GitHub ──────────► Action Worker ─────► Build / Deploy
```

<sub>
Build small · keep boundaries explicit · make failure recoverable.
</sub>
