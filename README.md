# Cut List Optimizer

Zaagoptimalisatie voor SOLIDWORKS weldments: leest de cut list, optimaliseert de zaaglengtes (minimaal materiaal én minimaal aantal zaagsnedes, inclusief verstek-nesting) en maakt een PDF-zaagplan met gekleurde balken, zaagvolgorde en reststukken.

## Download

Ga naar **[Releases](../../releases/latest)** en download:

- `CutListOptimizer_Setup_x.x.x.exe` — installer (aanbevolen): installeert de SolidWorks add-in én de losse app, registreert alles automatisch;
- of `CutListOptimizer_vx.x.x.zip` — losse bestanden met installatiescript, zie de LEESMIJ in de zip.

## Vereisten

Windows 10/11 (x64), SOLIDWORKS 2018 of nieuwer, .NET Framework 4.7.2+ (standaard aanwezig).

## Gebruik

1. Open een weldment-part of assembly in SolidWorks, rechtsklik op de Cut list > **Update**.
2. Klik op **Optimaliseer zaaglijst** (add-in) of start de Cut List Optimizer-app.
3. Stel handelslengte, zaagbladdikte, aantal producten en eventueel een eigen logo in.
4. De PDF opent automatisch.

Updates worden automatisch gemeld zodra hier een nieuwe versie verschijnt.
