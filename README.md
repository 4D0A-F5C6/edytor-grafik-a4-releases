# Edytor grafik A4 — wydania

Program dla Windows do układania obrazków na kartce A4: wklejasz grafiki,
ustawiasz je na stronie i drukujesz albo zapisujesz jako PDF.

To repozytorium zawiera **wyłącznie gotowe wydania programu**. Kodu źródłowego
tu nie ma i nie będzie.

## Instalacja

1. Wejdź w [Releases](../../releases) i pobierz plik
   `EdytorGrafikA4-<wersja>-instalator.exe` z najnowszego wydania.
2. Uruchom instalator. **Nie są potrzebne uprawnienia administratora** —
   program instaluje się dla bieżącego użytkownika.
3. Instalator zakłada skrót na pulpicie i w menu Start.

Windows może przy pierwszym uruchomieniu pokazać ostrzeżenie SmartScreen,
bo instalator nie ma płatnego podpisu wydawcy. Wybierz „Więcej informacji”
i „Uruchom mimo to”.

## Automatyczna aktualizacja

Od wersji 1.1.0 program sam sprawdza przy starcie, czy jest nowsze wydanie.
Jeśli jest, pobiera je w tle i **pyta, zanim cokolwiek zainstaluje** — możesz
wybrać instalację od razu albo przy zamykaniu programu.

Bez internetu program działa normalnie: sprawdzenie po prostu się nie udaje
i nie zobaczysz żadnego komunikatu o błędzie.

Numer zainstalowanej wersji widać na pasku stanu, w prawym dolnym rogu okna.

## Pliki w wydaniu

| Plik | Do czego służy |
|---|---|
| `EdytorGrafikA4-<wersja>-instalator.exe` | Instalator — to pobierasz ręcznie. |
| `latest.yml` | Informacja o wersji dla automatycznej aktualizacji. |
| `...exe.blockmap` | Pozwala aktualizacji pobrać tylko zmienione fragmenty. |
