# ped_hosting_test

App Flutter (web) bem simples — um contador — feito de exemplo.

## Rodando localmente

Pré-requisito: [Flutter SDK](https://docs.flutter.dev/get-started/install) instalado (`flutter doctor` sem erros).

```bash
flutter pub get
flutter run -d chrome        # roda no navegador
```

Para gerar o build de produção (web):
```bash
flutter build web --release
```
Os arquivos ficam em `build/web`.

## Estrutura do projeto
```
ped_hosting_test/
├── lib/main.dart
├── web/
├── pubspec.yaml
└── analysis_options.yaml
```
