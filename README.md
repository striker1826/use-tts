# @striker1826/use-tts

`@striker1826/use-tts`는 텍스트를 음성으로 변환하는 간단한 TypeScript 함수입니다. 이 함수는 브라우저의 `speechSynthesis` API를 사용하여 텍스트를 음성으로 변환합니다.

## 설치

이 패키지를 설치하려면 npm을 사용하십시오:

```bash
npm install @striker1826/use-tts
```

## 사용법

패키지를 가져와서 getSpeech 함수를 호출하여 텍스트를 음성으로 변환할 수 있습니다.

```bash
import { getSpeech } from '@striker1826/use-tts';

getSpeech('안녕하세요!');
```

## 함수 설명

```bash
getSpeech(text: string): void
```

주어진 텍스트를 음성으로 변환합니다.

### 매개변수

text: string - 음성으로 변환할 텍스트입니다.

## 브라우저 호환성

이 함수는 브라우저 환경에서만 작동합니다. Node.js 환경에서는 window 객체와 speechSynthesis API가 없기 때문에 작동하지 않습니다.

## 기여

기여를 환영합니다! 버그를 발견하거나 기능 요청이 있는 경우 이슈를 제출해 주세요.

## 라이선스

이 프로젝트는 MIT 라이선스 하에 배포됩니다. 자세한 내용은 LICENSE 파일을 참조하십시오.
