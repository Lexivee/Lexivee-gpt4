![248433934-7886223b-c1d1-4260-82aa-da5741f303bb](https://github.com/xtekky/gpt4free/assets/98614666/ea012c87-76e0-496a-8ac4-e2de090cc6c9)

By using this repository or any code related to it, you agree to the [legal notice](./LEGAL_NOTICE.md). The author is not responsible for any copies, forks, reuploads made by other users, or anything else related to gpt4free. This is the author's only account and repository. To prevent impersonation or irresponsible actions, please comply with the GNU GPL license this Repository uses.

Hier ist die Übersetzung des gegebenen Inhalts ins Deutsche:

```markdown
![248433934-7886223b-c1d1-4260-82aa-da5741f303bb](https://github.com/xtekky/gpt4free/assets/98614666/ea012c87-76e0-496a-8ac4-e2de090cc6c9)

Durch die Verwendung dieses Repositorys oder eines damit verbundenen Codes stimmen Sie dem [rechtlichen Hinweis](./LEGAL_NOTICE.md) zu. Der Autor ist nicht verantwortlich für Kopien, Forks, erneute Uploads, die von anderen Benutzern gemacht wurden, oder für alles andere, was mit gpt4free zu tun hat. Dies ist das einzige Konto und Repository des Autors. Um Nachahmung oder unverantwortliches Handeln zu verhindern, halten Sie sich bitte an die GNU GPL-Lizenz, die dieses Repository verwendet.

### Neu

- pypi-Paket:

```
pip install -U g4f
```

## Inhaltsverzeichnis:

- [Inhaltsverzeichnis:](#inhaltsverzeichnis)
- [Erste Schritte](#erste-schritte)
  - [Voraussetzungen:](#voraussetzungen)
  - [Projekt einrichten:](#projekt-einrichten)
    - [Installation über pypi](#installation-über-pypi)
    - [oder](#oder)
    - [Einrichtung mit Docker:](#einrichtung-mit-docker)
- [Verwendung](#verwendung)
  - [Das `g4f` Paket](#das-g4f-paket)
  - [Interferenz openai-Proxy-API (Verwendung mit openai Python-Paket)](#interferenz-openai-proxy-api-verwendung-mit-openai-python-paket)
- [Modelle](#modelle)
  - [gpt-3.5 / gpt-4](#gpt-35--gpt-4)
  - [Andere Modelle](#andere-modelle)
- [Verwandte gpt4free-Projekte](#verwandte-gpt4free-projekte)
- [Beitragen](#beitragen)
- [ChatGPT-Klon](#chatgpt-klon)
- [Urheberrecht:](#urheberrecht)
- [Urheberrechtshinweis:](#urheberrechtshinweis)
- [Sternverlauf](#sternverlauf)

## Erste Schritte

#### Voraussetzungen:

1. [Python herunterladen und installieren](https://www.python.org/downloads/) (Version 3.x wird empfohlen).

#### Projekt einrichten:

##### Installation über pypi

```
pip install -U g4f
```

##### oder

1. GitHub-Repository klonen:

```
git clone https://github.com/xtekky/gpt4free.git
```

2. Zum Projektverzeichnis navigieren:

```
cd gpt4free
```

3. (Empfohlen) Eine virtuelle Umgebung erstellen, um Python-Pakete für Ihr Projekt zu verwalten:

```
python3 -m venv venv
```

4. Die virtuelle Umgebung aktivieren:
   - Unter Windows:
   ```
   .\venv\Scripts\activate
   ```
   - Unter macOS und Linux:
   ```
   source venv/bin/activate
   ```
5. Die erforderlichen Python-Pakete aus `requirements.txt` installieren:

```
pip install -r requirements.txt
```

6. Eine `test.py`-Datei im Hauptverzeichnis erstellen und das Repo verwenden, weitere Anweisungen finden Sie unten.

```py
import g4f

...
```

##### Einrichtung mit Docker:

Wenn Docker installiert ist, können Sie das Projekt einfach einrichten und ausführen, ohne die Abhängigkeiten manuell zu installieren.

1. Stellen Sie sicher, dass sowohl Docker als auch Docker Compose installiert sind.

   - [Docker installieren](https://docs.docker.com/get-docker/)
   - [Docker Compose installieren](https://docs.docker.com/compose/install/)

2. GitHub-Repo klonen:

```bash
git clone https://github.com/xtekky/gpt4free.git
```

3. Zum Projektverzeichnis navigieren:

```bash
cd gpt4free
```

4. Das Docker-Image erstellen:

```bash
docker compose build
```

5. Den Dienst mit Docker Compose starten:

```bash
docker compose up
```

Ihr Server läuft jetzt unter `http://localhost:1337`. Sie können wie gewohnt mit der API inter

agieren.

## Verwendung

### Das `g4f` Paket

Das `g4f`-Paket ermöglicht es Ihnen, mit dem Modell zu interagieren und Anfragen zu senden. Es ist ein einfacher Wrapper um die OpenAI-API.

### Interferenz openai-Proxy-API (Verwendung mit openai Python-Paket)

Mit dieser API können Sie das Modell über die OpenAI Python-Bibliothek verwenden. Es stellt sicher, dass Sie die gleiche Erfahrung wie mit der offiziellen OpenAI-API haben.

## Modelle

### gpt-3.5 / gpt-4

Dieses Repository enthält Modelle der Versionen gpt-3.5 und gpt-4. Sie können diese Modelle verwenden, um Texte zu generieren oder zu vervollständigen.

### Andere Modelle

Es gibt auch andere Modelle, die Sie verwenden können. Weitere Informationen finden Sie in den Dokumenten.

## Verwandte gpt4free-Projekte

Es gibt viele andere Projekte, die mit gpt4free in Verbindung stehen. Einige von ihnen sind offizielle Projekte, andere sind von der Community erstellt. Sie können diese Projekte verwenden, um Ihre eigenen Anwendungen zu erstellen oder um mehr über gpt4free zu erfahren.

## Beitragen

Wenn Sie zu diesem Projekt beitragen möchten, können Sie dies tun, indem Sie einen Pull-Request senden oder ein Problem melden. Alle Beiträge sind willkommen.

## ChatGPT-Klon

Es gibt einen ChatGPT-Klon, der auf diesem Repository basiert. Sie können ihn verwenden, um mit dem Modell zu chatten und Fragen zu stellen.

## Urheberrecht:

Alle Rechte vorbehalten. Kein Teil dieses Repositorys darf ohne die ausdrückliche schriftliche Genehmigung des Urhebers reproduziert oder übertragen werden.

## Urheberrechtshinweis:

Dieses Repository und alle damit verbundenen Dateien sind urheberrechtlich geschützt. Jede unerlaubte Verwendung kann rechtliche Konsequenzen nach sich ziehen.

## Sternverlauf

Der Sternverlauf zeigt die Anzahl der Sterne, die dieses Repository im Laufe der Zeit erhalten hat. Es hilft, die Popularität des Projekts zu verfolgen.
```

