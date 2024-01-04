# Turborepo Monorepo

> 📦 Turborepo practice repository

<br />

## Turborepo 란?

Vercel이 인수한 Turborepo는 JavaScript와 TypeScript 코드 베이스의 모노레포를 위한 `고성능 빌드 시스템 도구`
<br />

Vercel과 AWS, Miro, PayPal, Discord, LINE+의 Universal Video Player 등
<br />
여러 프로젝트에서 프로덕션 단계로 사용하고 있으며, 지금도 활발하게 개발이 진행되고 있다.

<br />

## Turborepo 특징

- 꼭 모노레포에서만 사용하는 것은 아니다.
- 모노레포의 경우에는 `npm` `yarn classic` `yarn berry` `pnpm`의 워크스페이스와 함께 사용 가능하지만 `pnpm`를 권장하고 있다.
- 프로젝트의 루트 혹은 각 워크스페이스에 **turbo.json** 이라는 파일을 이용해 `캐싱`과 `태스크 오케스트레이션`을 설정한다.

<br />

## Turborepo 장점

- 사용자가 빌드한 내용을 기억하고 이미 계산한 내용은 건너뛰게된다.<br />즉, 태스크 설정 만으로 기본값이 캐싱한다라는 뜻이다.
- Turborepo는 **타음스탬프**가 아닌 **파일 내용**을 보고 빌드해야 할 내용을 파악한다.
- 쉬고 있는 CPU를 낭비하지 않고, 모든 코어를 최대로 사용해서 병렬로 실행할 수 있다.
- 원격 빌드 캐시를 팀원 및 **CI/CD**와 공유하여 빌드 속도를 더욱 높일 수 있다.
- **작업 간의 관계**를 정의한 다음 Turborepo가 빌드할 항목과 시기를 최적화할 수 있다.

<br />

## Turborepo 주요 기능

### `Running Tasks`

...

### ...

```shell
turbo run build
turbo run build --filter=shared
turbo run lint test build
turbo gen workspace
turbo login
turbo link
```
