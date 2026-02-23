# Fivem-Scripts

Repository dedicat exclusiv scripturilor FiveM:
- standalone (fara framework)
- Qbox (compatibile cu framework-ul Qbox)

## Structura recomandata

```text
standalone/
qbox/
```

Poti organiza fiecare resursa in folderul potrivit, de exemplu:

```text
standalone/my_resource/
qbox/qbx_my_resource/
```

## Reguli pentru acest repo

- Nu adauga scripturi pentru alte framework-uri (ESX, QBCore clasic etc.) aici.
- Pastreaza fiecare script ca resource separat (cu propriul `fxmanifest.lua`).
- Foloseste denumiri clare, orientate pe functionalitate.

## Commit convention (simplu)

- `feat:` functionalitate noua
- `fix:` bug fix
- `chore:` mentenanta/configurare

Exemplu:

```text
feat(qbox): add banking helper export
fix(standalone): prevent nil callback on player drop
```
