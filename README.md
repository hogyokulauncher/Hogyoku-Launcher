# Hogyoku-Launcher
Minecraft: Java Edition용 독립 Windows 런처
# Hogyoku Launcher

Hogyoku Launcher는 Minecraft: Java Edition을 위한 독립 Windows 데스크톱 런처입니다.

## 목적

Hogyoku Launcher는 Minecraft: Java Edition을 정식으로 소유한 사용자가 자신의 개인 Microsoft 계정으로 인증하고 전용 Windows 런처를 통해 게임을 실행할 수 있도록 개발되고 있습니다.

인증 흐름은 다음과 같습니다.

Microsoft OAuth  
→ Xbox Live 인증  
→ XSTS  
→ Minecraft Services

## 인증 및 개인정보 보호

- 사용자는 Microsoft를 통해 직접 로그인합니다.
- Hogyoku Launcher는 Microsoft 계정 비밀번호를 수집하지 않습니다.
- Hogyoku Launcher는 자체 Microsoft Entra Application ID를 사용합니다.
- 다른 런처의 Application ID를 재사용하거나 가장하지 않습니다.
- 사용자는 Minecraft: Java Edition을 정식으로 소유하고 있어야 합니다.
- 인증 토큰은 로그나 명령줄 인수에 노출되지 않도록 설계하고 있습니다.

## 지원 플랫폼

- Windows 10
- Windows 11
- Minecraft: Java Edition

## 개발 상태

Hogyoku Launcher는 현재 개발 중입니다.

현재 Microsoft OAuth, Xbox 사용자 인증, XSTS 인증 단계까지 정상적으로 검증되었습니다.

Minecraft Services 사용을 위한 Application ID 검토 및 승인을 기다리고 있습니다.

## 배포

현재 이 저장소는 Hogyoku Launcher 프로젝트의 공개 정보 페이지 용도로 사용됩니다.

Minecraft 게임 파일이나 제3자의 독점 바이너리는 배포하지 않습니다.

## 면책 조항

Hogyoku Launcher는 독립 프로젝트이며 Microsoft, Mojang Studios 또는 Minecraft와 공식적으로 제휴하거나 보증받은 프로젝트가 아닙니다.
