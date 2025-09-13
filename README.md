# Aurora Celestial — Entry for R3x

Single-file site:
- Purple door → butterflies + star rain
- Tabs: WHY? · Visuales experimento r3x.mp4 · Interacción con el algoritmo
- Gallery renders IPFS CIDs (tries video first, then image fallback + link)
- Analyzer (client-side): drag&drop .wav/.mp3/.m4a or .mp4; 120s best-energy segment; waveform + spectrum; RMS/ZCR/dominant freq/centroid/BPM; download JSON.

## Use
Just open `index.html` in a modern browser (Chrome/Edge/Firefox). No server needed.

## Notes
- Some IPFS gateways may block media ranges/CORS; the code hints `?filename=clip.mp4` to help them serve as video. If not playable, card falls back to image + open link.
- Video analysis extracts audio via Web Audio API; playback must be user-initiated (click Analyze).
