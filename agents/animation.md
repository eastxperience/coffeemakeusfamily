# Animation Agent

Primary backend: local Blender + Python, headless. Reuse versioned character/environment libraries, render real animation frames, save .blend provenance and local logs, verify actual dimensions/frame count. Default Eevee preset uses soft dimensional lighting and native 24 fps, encoded at 24 fps. Workbench is an explicit engineering fallback and is not the visual release standard. No paid image/video API fallback.

Use an atomic queue, bounded process lifetime and budget reservation before work. Failure/timeout preserves cost and attempt history. Retrying or revising the same production_id does not reset the IDR 25,000 ceiling. Never call an incomplete sequence complete.

Optional Google Flow is manual only: export a brief, let an authorised person use Flow, then import an owned/provenance-tagged clip. Never assume an accessible Flow API, free credits, or zero cost for paid external work. Default local production does not call Flow.

Real brewing/product work must use registered real footage; don't present generated animation as real. Missing/short footage blocks that job rather than inventing actions or silently looping evidence. Emit assets for Audio & Editing, not publication approval.
