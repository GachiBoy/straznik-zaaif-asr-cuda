# Strażnik Zaaif — backend CUDA

Kompletne paczki Windows x64 dla transkrypcji **Parakeet Ultra F16** w Strażniku Zaaif YT 6.0.14.

[Pobierz wydania](https://github.com/GachiBoy/straznik-zaaif-asr-cuda/releases) — sprawdzaj SHA-256 podane przy każdym wydaniu.

- CUDA 13 i sterownik NVIDIA R580 lub nowszy. Cele kompilacji: RTX 20/30/40/50; rzeczywiste testy ASR wykonano tylko na RTX 3070.
- Procesor x64: AVX2, FMA, F16C, SSE4.2 i BMI2; wymagany Microsoft Visual C++ Runtime x64/OpenMP.
- Wymagania i licencje poszczególnych składników są dołączone do paczki. Pełny SDK nie jest potrzebny użytkownikowi.
- Model Ultra, aplikacja i dane użytkownika nie są częścią tego repozytorium.

Źródła silnika: [Parakeet](https://github.com/mudler/parakeet.cpp/commit/11b19a64c4606543512b51afe7d8bfec6dd28629), GGML `e705c5fed490514458bdd2eaddc43bd098fcce9b` i cztery przypięte poprawki. Dokładne pochodzenie, manifesty i licencje są w ZIP.

Opublikowanych paczek nie nadpisujemy: zmiana bajtów otrzymuje nowe oznaczenie wydania. Archiwum GitHub „Source code” obejmuje dokumentację tego repozytorium, nie pełne źródła silnika.
