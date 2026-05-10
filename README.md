# visionOS-Playground-Tutorials

Apple의 visionOS 공식 튜토리얼을 기반으로 공간 컴퓨팅 앱 개발의 기초를 학습하고 기록하는 저장소입니다.

이 저장소는 단순히 튜토리얼을 따라 하는 것을 넘어, visionOS 앱이 어떤 구조로 동작하는지 이해하고 실제 프로젝트로 확장할 수 있는 개발 기반을 만드는 것을 목표로 합니다.

---

## Purpose of This Repository

이 레포지토리는 Apple의 visionOS 공식 튜토리얼을 기반으로 공간 컴퓨팅 앱 개발을 위한 기초 지식과 개발 역량을 쌓기 위해 만들어졌습니다.

visionOS는 기존의 2D 앱과 다르게 Window, Volume, Space와 같은 공간 기반 UI 구조를 사용합니다.  
따라서 이 저장소에서는 튜토리얼을 따라 구현하는 것뿐만 아니라, 각 구조가 왜 필요한지, 어떻게 동작하는지, 실제 앱 개발에서는 어떻게 활용될 수 있는지를 함께 정리합니다.

### 이 저장소에서 다루는 내용

- visionOS 앱 구조 이해
- SwiftUI 기반 UI 구성 방식 학습
- 공간 환경에서의 앱 동작 방식 이해
- visionOS 앱 라이프사이클과 데이터 흐름 이해
- 기존 2D 앱과 공간 컴퓨팅 앱의 구조적 차이 비교
- 실제 프로젝트로 확장 가능한 개발 기반 구축

---

## What I Focus On

### 1. visionOS의 기본 UI 구조 이해

visionOS 앱에서 사용되는 핵심 UI 구조를 학습합니다.

- Window
- Volume
- Space

각 개념이 어떤 상황에서 사용되는지, 기존 iOS 앱의 화면 구조와 어떤 차이가 있는지 정리합니다.

### 2. SwiftUI 기반 앱 구조 및 화면 구성

SwiftUI를 활용해 visionOS 앱의 화면과 인터랙션을 구현합니다.

특히 다음과 같은 내용을 중심으로 학습합니다.

- View 구성 방식
- State와 데이터 흐름
- WindowGroup 구조
- SwiftUI modifier의 역할
- visionOS 환경에서의 레이아웃 동작 방식

### 3. visionOS 앱 라이프사이클과 데이터 흐름 이해

앱이 실행되고, 화면이 생성되고, 사용자의 상호작용에 따라 상태가 변경되는 흐름을 이해합니다.

단순히 코드가 실행되는 결과만 보는 것이 아니라, 앱의 구조와 데이터가 어떤 방향으로 흐르는지 함께 분석합니다.

### 4. 기존 2D 앱과 공간 컴퓨팅 앱의 차이 이해

기존 iOS 앱은 주로 화면 안에서의 UI 구성이 중심이지만, visionOS 앱은 공간 안에서의 배치와 사용자 경험이 중요합니다.

이 저장소에서는 다음과 같은 차이를 중심으로 학습합니다.

- 평면 UI와 공간 UI의 차이
- 창 크기와 콘텐츠 크기의 관계
- 사용자가 앱을 공간에 배치하는 방식
- 몰입형 경험과 일반 앱 경험의 차이

### 5. Apple 공식 튜토리얼 기반 실습

Apple Developer의 공식 튜토리얼을 직접 따라 구현하며 핵심 개념을 코드로 확인합니다.

튜토리얼을 완료한 뒤에는 각 챕터별 README를 통해 배운 점, 어려웠던 점, 궁금한 점을 기록합니다.

---

## Preview

> 시뮬레이터 GIF 또는 이미지 추가 예정

```text
(Add simulator GIF or images here)
```

---

## Repository Structure

```text
visionOS-Playground-Tutorials/
│
├── Chapter1/
│   └── WindowsInVisionOS/
│       ├── [Project Files]
│       └── README.md
│
├── Chapter2/
│   └── ...
│
├── Chapter3/
│   └── ...
│
└── README.md
```

각 챕터는 다음 내용을 포함합니다.

- 실습 프로젝트 코드
- 챕터별 README
- 학습 기록 및 회고
- 핵심 개념 정리
- 어려웠던 부분과 해결 과정

---

## Learning Approach

이 저장소는 다음과 같은 흐름으로 학습을 진행합니다.

1. Apple 공식 튜토리얼 기반 기능 구현
2. 코드 구조 및 동작 방식 분석
3. 핵심 개념 정리
4. 이해하기 어려웠던 부분 기록
5. 실제 앱 개발에 적용 가능한 형태로 재해석

단순히 결과물을 만드는 것보다, “왜 이 구조를 사용하는가”를 이해하는 것에 집중합니다.

---

## 📝 Chapter Documentation

각 챕터의 README는 다음 구조로 작성됩니다.

```text
📌 Summary
🧠 What I Learned
🔍 Key Concepts
💡 What Was Interesting
❗ Difficulties
❓ Questions
🚀 Next Step
```

### Chapter README Template

```markdown
# Chapter Title

## 📌 Summary

이 챕터에서 학습한 내용을 간단히 요약합니다.

## 🧠 What I Learned

이 챕터를 통해 새롭게 배운 내용을 정리합니다.

## 🔍 Key Concepts

핵심 개념을 정리합니다.

## 💡 What Was Interesting

흥미로웠던 부분이나 새롭게 느낀 점을 기록합니다.

## ❗ Difficulties

이해하기 어려웠던 부분이나 막혔던 부분을 기록합니다.

## ❓ Questions

추가로 궁금한 점을 정리합니다.

## 🚀 Next Step

다음에 학습하거나 개선할 내용을 기록합니다.
```

---

## Goal

이 저장소의 목표는 다음과 같습니다.

- visionOS 개발의 기초 개념을 정확히 이해하기
- 공간 컴퓨팅 앱 개발을 위한 기술 기반 구축하기
- SwiftUI 기반 앱 구조에 익숙해지기
- 튜토리얼을 넘어 실제 앱 개발로 확장하기
- 학습 과정을 기록하며 개발자로서의 성장 과정 남기기

---

## References

- [Apple Developer - visionOS](https://developer.apple.com/visionos/)
- [SwiftUI Documentation](https://developer.apple.com/documentation/swiftui)
- [Human Interface Guidelines](https://developer.apple.com/design/human-interface-guidelines)
- [Creating your first visionOS app](https://developer.apple.com/documentation/visionos/creating-your-first-visionos-app)

---

## Author

**Seojin Lee**  
Developer
Apple Developer Academy @ POSTECH Cohort 2026

---

## Note

이 레포지토리는 완성된 결과물이 아니라 학습 과정과 개발 역량을 쌓는 기록입니다.

튜토리얼을 따라가며 배운 내용을 정리하고, 이해한 내용을 나만의 언어로 다시 설명하는 것을 목표로 합니다.

This repository is not a finished product, but a record of learning and building development capability.
