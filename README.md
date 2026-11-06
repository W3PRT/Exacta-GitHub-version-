# Exacta Engineering Calculator

A fresh Android Studio project for an offline scientific and power-systems calculator.

## Included in this first build
- Casio fx-991ES Plus-inspired white calculator interface
- LCD-style expression/result display
- Scientific expression parser: arithmetic, parentheses, powers, factorial, pi, e, trig/inverse trig, hyperbolic, logarithms, square root, absolute value
- DEG/RAD toggle
- Calculation history (in-memory for this initial build)
- Engineering menu
- IEC 60255 standard/very/extremely/long-time inverse overcurrent time calculation
- Distance relay primary-to-secondary zone impedance conversion
- Preliminary high-impedance REF screening estimate
- Three-phase transformer rated current and simplified terminal fault estimate
- Balanced three-phase power calculation

## Open and build
1. Install Android Studio (Hedgehog or newer).
2. Open this folder as a project.
3. Use JDK 17.
4. Allow Gradle sync to complete.
5. Connect an Android device or start an emulator.
6. Select Run.

To build an APK: **Build > Build Bundle(s) / APK(s) > Build APK(s)**.

## Important limitations
This is a working starter implementation, not yet a complete fx-991ES Plus emulator or a certified protection-setting package. The REF calculation is explicitly a preliminary screening estimate and must not be used as a final design. Distance earth-loop compensation, relay-specific algorithms, full CT/VT testing, matrix/vector/statistics, persistent storage, report export and automated validation suites remain future development work. Always verify protection settings against the relay manual, approved protection philosophy and coordination study.
