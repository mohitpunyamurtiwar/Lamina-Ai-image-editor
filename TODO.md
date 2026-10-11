# LUMINA EDITOR UPGRADE TODO
Status: 0/28 complete (Updated after each step)

## Priority 1: Bug Fixes (Steps 1-5)
- [x] 1. Add Claude API key input + auth headers + fallback heuristics
- [x] 2. Fix HSL/grade zone slider key mapping (dynamic state preservation)
- [ ] 3. Implement crop tool (handles/aspect/apply mask)
- [ ] 4. Implement perspective transform (matrix on canvas)
- [ ] 5. Migrate renderImage to WebGL shaders (LUT/curves/basic filters)

## Priority 2: UI Redesign (Steps 6-12)
- [ ] 6. Top bar: Add module selector (Develop/Color/Scopes)
- [ ] 7. Left panel: Add Scopes tab (vectorscope/waveform/parade)
- [ ] 8. Right panels: Add Color Wheels, Qualifiers, Power Windows, Layer panel
- [ ] 9. Canvas overlays: Scopes preview, onion-skin
- [ ] 10. Bottom: Timeline/history panels
- [ ] 11. Keyboard shortcuts (DaVinci JKL, alt-drag)
- [ ] 12. Touch/PWA optimizations

## Priority 3: Add 100+ Tools (Steps 13-22)
- [ ] 13. Light/Tone: +20 sliders (Clarity/Microcontrast/Texture/Split-tone/Orton)
- [ ] 14. Color: +25 (Wheels/Qualifiers/Gradient Map/Selective)
- [ ] 15. Geometry: +15 (Liquify/Warp/Content-Aware/Lens profiles)
- [ ] 16. Detail/Repair: +20 (Clone/RedEye/FreqSep/SurfaceBlur)
- [ ] 17. Effects/FX: +30 shaders (Bloom/Grain/Anamorphic/LUTs)
- [ ] 18. AI/ML: +15 (SuperRes/ObjectRemove/SkyReplace/Upscale)
- [ ] 19. Masks/Layers: Brush panel, non-destructive stack
- [ ] 20. Pro: RAW/Batch/Print/Proofing
- [ ] 21. Scopes: Vectorscope/Waveform/Parade histograms
- [ ] 22. History/Non-destructive full pipeline

## Priority 4: Perf & Validation (Steps 23-28)
- [ ] 23. Full WebGL shader migration (all filters)
- [ ] 24. Error handling/try-catch everywhere
- [ ] 25. Responsive/touch full support
- [ ] 26. Test: Browser open, large image perf (60FPS)
- [ ] 27. Validate: 130+ tools, no console errors
- [ ] 28. Final optimizations/export presets

**Next step:** Begin edits on lumina-editor.html (Priority 1 bugs first).

