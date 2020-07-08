# W906_BR-TH
W906 Thaqi Breitenmoser


## Planung


## Versionsverwaltung
Für die Versionsverwaltung haben wir uns für Github entschieden. Der Grund dafür ist, dass wir von den verschiedenen Tools die es gibt, Github am besten kennen und einfach zu integrieren ist. Wir haben dafür die Repository "https://github.com/kebab8902/W906_BR-TH" erstellt.


## Code
Unser Code besteht aus einem kleinem HTML-File und einem Docker-file. Unser Dockerfile baut einen Apache 2 Webserver deren Index aus unserem HTML-File besteht. Das HTML-File besteht aus ein paar Zeilen Code und gibt "Hello World" aus.

## Build
Damit wir unser Projekt builden können, haben wir Google Cloud ausgewählt. Google Cloud Platform ermöglicht es ganz einfach unsere Projekte zu builden. Wir können damit verschiedene Trigger aufsetzen die beim Auslösen das Projekt builden. Unser Haupttrigger ist, dass wenn ein Dockerfile gepushed wird, dass er dieses File automatisch builded.

## Continuous Integration
Für CI haben wir uns für Jenkins entschieden. Bei unserer Recherche haben wir hauptsächlich nur Gutes gehört. Der Support der Community ist sehr hilfreich. Da wir Google Cloud verwenden, konnten wir ganz einfach Jenkins integrieren.

## Continuous Delivery
Kubernetes
