# My ceiling — person detection on the ESP32-S3

<!--
Session 6. Fill this in as you go, then commit it as "FINAL: my ceiling".
- 96 × 96: GUESS the time before you flash, then write the measured time.
- 160 × 160 and 48 × 48: PREDICT from your measured 96 px time
  (× 2.8 and ÷ 4 — slide "More pixels, more stops"), then measure.
- Accuracy: the validation accuracy on Edge Impulse's "Transfer learning" page
  after training (for 96 px it is already there in the cloned project).
- Last line: one sentence — speed, memory, or nothing in your tests.
-->

| Image size | My prediction             | Measured | FPS | Accuracy |
|------------|---------------------------|----------|-----|----------|
| 96 × 96    | guess: ... ms             | ... ms   | ... | ... %    |
| 160 × 160  | 96 px time × 2.8 = ... ms | ... ms   | ... | ... %    |
| 48 × 48    | 96 px time ÷ 4 = ... ms   | ... ms   | ... | ... %    |

What limited my board: ...
