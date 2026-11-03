
# 1단계 헤더 (제목)
## 2단계 헤더 (소제목)

**굵은 글씨 (Bold)** 및 *기울임꼴 (Italic)* 테스트

---

### 1. 목록 (List) 및 제약 조건
* negative constraint 준수 여부 확인
* 팩트체크 출처 명시
  * 1차 출처: 학술 논문 및 공식 문서

### 2. 표 (Table) 포맷팅 (AI 오류가 자주 나는 부분)
| 모델 구분 | 지시 이행 (Instruction) | 환각 여부 (Hallucination) | 최종 점수 |
| :--- | :---: | :---: | :--- |
| **Model A** | Pass | No Error | **4.5 / 5.0** |
| **Model B** | Fail | High Error | **2.0 / 5.0** |

### 3. 코드 블록 (Code Block)
```python
def check_factuality(response, source):
    if response == source:
        return "Pass"
    return "Fail"