# MauiAppHotel

Aplicativo desenvolvido em **.NET MAUI** focado na plataforma **Android**, para gerenciamento de hospedagens.  
Permite simular a contratação de quartos, exibindo informações de check-in, check-out e quantidade de hóspedes.

## Funcionalidades

- Cadastro e seleção de quartos disponíveis  
- Definição de datas de check-in e check-out  
- Cálculo e exibição de informações da hospedagem  
- Tela "Sobre" com informações do desenvolvedor  
- Interface com barra de navegação inferior (Shell TabBar)

## Execução no Android

### Pré-requisitos
- .NET 8 SDK ou superior  
- Workload **maui-android** instalado  
- Android SDK / Emulator configurado  
- Visual Studio 2022 (opcional) ou ambiente CLI (Linux/macOS)

### Instalar workload MAUI Android

```bash
dotnet workload install maui-android
```

### Comandos principais

```bash
# Restaurar dependências
dotnet restore

# Compilar para Android
dotnet build -f net8.0-android

# Executar no emulador ou dispositivo conectado
dotnet build -t:Run -f net8.0-android
```

## Desenvolvedor

**Rodrigo Oliveira**  
**2025**
