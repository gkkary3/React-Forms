# React 폼 데이터 처리 및 유효성 검사 예제

React에서 폼 데이터를 처리하는 다양한 방법을 살펴보는 예제 프로젝트입니다. 각 방법은 `useState`, `useRef`, `FormData`를 사용해 각각의 방식으로 폼 데이터를 관리하고 유효성 검사를 수행하는 방법을 설명합니다.

---

## 사용 방법

1. **useState 사용하기**

   <img src="https://github.com/user-attachments/assets/3732062b-0065-4e50-bd91-388bd1114267" width="500"/>

   - **설명**: `useState`를 활용하여 `input` 값들을 관리하고, `onBlur` 이벤트로 사용자의 입력을 실시간으로 검증합니다.  
   - **특징**: 입력이 변경될 때마다 상태가 업데이트되어 유효성 검사가 즉시 적용됩니다.

2. **useRef 사용하기**

   <img src="https://github.com/user-attachments/assets/b72b2403-a29f-4b51-b822-65f8eb132e9c" width="500"/>

   - **설명**: `useRef`를 이용해 `input` 요소에 접근하여, 데이터를 제출할 때(`onSubmit`) 한 번에 유효성 검사를 수행합니다.  
   - **특징**: 상태 변경 없이 입력 요소를 직접 참조해 유효성 검사를 수행하므로 퍼포먼스 측면에서 유리합니다.

3. **FormData 사용하기**

   ![FormData 예제](https://github.com/user-attachments/assets/a0e27ade-5dd4-4bb9-9e0f-8559138cee4e)

   - **설명**: `FormData` 객체를 활용해 `form` 태그 안의 모든 `input` 데이터를 관리하며, `required` 속성을 통해 기본적인 유효성 검사를 설정할 수 있습니다.  
   - **특징**: 폼 데이터 전체를 쉽게 관리할 수 있으며, HTML 기본 유효성 검사를 활용할 수 있습니다.

---

## 데모

이 프로젝트를 클론하여 로컬 환경에서 실행하고, 각 폼 관리 방법에 따른 입력 및 유효성 검사 과정을 확인할 수 있습니다.

---

## 설치 및 실행

1. 이 리포지토리를 클론합니다:

   ```bash
   git clone https://github.com/yourusername/react-form-handling.git
