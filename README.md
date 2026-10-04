# Astrela para Android

Navegador móvel nativo para Android, com motor GeckoView, abas privadas separadas e controles pensados para uso com uma mão. Este é o canal público das versões oficiais do Astrela: cada lançamento traz APKs assinados e suas notas de versão.

**[Ver lançamentos e baixar APK](https://github.com/luarxx/astrela-releases/releases)**

Se a página estiver vazia, ainda não há versões publicadas.

## Escolha o APK

Cada lançamento inclui uma versão para cada arquitetura:

| Arquivo | Use em |
| --- | --- |
| `Astrela-vX.Y.Z-arm64-v8a.apk` | Aparelhos com processador ARM de 64 bits (ARM64) |
| `Astrela-vX.Y.Z-x86_64.apk` | Aparelhos com processador x86 de 64 bits (x86_64) |

Confira a arquitetura do aparelho antes de baixar. Um APK de arquitetura incompatível não será instalado.

## Instalar no Android

1. Abra a [página de lançamentos](https://github.com/luarxx/astrela-releases/releases), escolha a versão mais recente e baixe o APK compatível com seu aparelho.
2. Abra o arquivo baixado na pasta **Downloads**.
3. Se o Android solicitar, permita a instalação para o navegador ou gerenciador de arquivos usado no download e confirme a instalação nas telas do sistema.

## Atualizar o Astrela

Instale o APK da nova versão sobre a instalação atual e confirme a atualização no Android. Não é necessário desinstalar o app primeiro.

Quando o Astrela detectar uma nova versão, ele pode exibir um aviso com acesso à página de lançamento. O download e a instalação continuam sob seu controle e a confirmação final é feita pelo Android.

## Arquivos de cada lançamento

- **APK ARM64 e APK x86_64**: builds assinadas do app para as arquiteturas indicadas.
- **`SHA256SUMS`**: hashes SHA-256 dos APKs para conferência opcional.
- **`latest.json`**: manifesto público usado pelo Astrela para consultar a versão disponível e abrir a página do lançamento.

Para conferir o hash de um APK no Windows PowerShell, calcule-o e compare o valor `Hash` com a linha correspondente em `SHA256SUMS`:

```powershell
Get-FileHash .\Astrela-vX.Y.Z-arm64-v8a.apk -Algorithm SHA256
```

As notas e os arquivos são publicados na página de cada [lançamento](https://github.com/luarxx/astrela-releases/releases).
