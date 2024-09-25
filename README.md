# Introduksjon til LangChain og LangGraph

Dette prosjektet inneholder en Quarto presentasjon om LangChain og LangGraph.
Presentasjonen er ment å gi en grunnleggende introduksjon til tankegangen bak
LangChain og LangGraph og hvordan disse to prosjektene passer sammen.

> [!TIP]
> Bruk `uv sync` for å installere prosjektet og avhengighetene automagisk.

## Presentere

For å presentere Quarto presentasjonen bruk:

```bash
quarto preview --execute
```

## For å kjøre eksemplene

For å kunne kjøre koden i presentasjonen så trenger man et GCP prosjekt.
Deretter må man aktivere `Vertex AI` komponenten i GCP, dette kan gjøres på
[console.cloud.google](https://console.cloud.google.com/flows/enableapi?apiid=aiplatform.googleapis.com).

Deretter er det bare å hente `Application Default Credentials` med `gcloud`:

```bash
gcloud auth application-default login
# Husk å sette riktig prosjekt med
# gcloud config set project <navn_på_prosjekt>
```

> [!TIP]
> Se [`pyproject.toml`](pyproject.toml) for Python avhengigheter for å kjøre koden.
