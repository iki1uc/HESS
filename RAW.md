┌──────────────────────────────────────────────┐
│                12D AIR‑TENSOR                │
├───────────────┬───────────────┬─────────────┤
│ 6D CLASSIC     │ 6E EXTENDED   │ META        │
├───────────────┼───────────────┼─────────────┤
│ pos_x          │ lage_value    │ Slide_tri   │
│ pos_y          │ tiefe_value   │ Speed³      │
│ piece_type     │ momentum_value│ Bonus       │
│ color          │ slide_value   │ ΔTime       │
│ vector_dir     │ speed3_value  │ ΔDepth      │
│ carry_effect   │ bonus_value   │ ΔMomentum   │
└───────────────┴───────────────┴─────────────┘
┌──────────────────────────────────────────────┐
│                9×9 BOARD‑TENSOR              │
├──────────────────────────────────────────────┤
│ d1 d2 d3 d4 d5 d6 d7 d8 d9                   │
│ e1 e2 e3 e4 e5 e6 e7 e8 e9                   │
│ i1 i2 i3 i4 i5 i6 i7 i8 i9                   │
│ n1 n2 n3 n4 n5 n6 n7 n8 n9                   │
│ o1 o2 o3 o4 o5 o6 o7 o8 o9                   │
│ r1 r2 r3 r4 r5 r6 r7 r8 r9                   │
│ s1 s2 s3 s4 s5 s6 s7 s8 s9                   │
│ u1 u2 u3 u4 u5 u6 u7 u8 u9                   │
│ w1 w2 w3 w4 w5 w6 w7 w8 w9                   │
└──────────────────────────────────────────────┘
        t3³
       ╱
      ╱
     t2²
    ╱
   ╱
  t1
        t3³
       ╱
      ╱
     t2²
    ╱
   ╱
  t1
     Slide_tri = (t1 × 1) + (t2 × 2)² + (t3 × 3)³
┌───────────────┐
│ SPEED³‑TENSOR │
├───────────────┤
│ 3 × 3³ = 81    │
└───────────────┘
┌──────────────────────────────┐
│      EBENEN‑TRAVERSAL        │
├───────────────┬──────────────┤
│ E1 Board       │ 9×9          │
│ E2 Vector      │ 12D          │
│ E3 Slide       │ Triangular   │
│ E4 Speed       │ X4 / X8      │
│ E5 Bonus       │ Kill‑Boost   │
│ E6 HESS        │ Battle‑Mode  │
└───────────────┴──────────────┘

Traversal:
E1 → E2 → E3 → E4 → E5 → E6 → E1 → …
┌──────────────────────────────┐
│      WIRKUNGSGRAD‑TENSOR     │
├──────────────────────────────┤
│ W = AXIOM + PUZZLE + Slide   │
│ Slide = L + T + M + Tri + S³ │
└──────────────────────────────┘
UNLINEAR(Zug) = Σ(12D) × Ebenen(6) × Slide³ × Speed³

      
    
