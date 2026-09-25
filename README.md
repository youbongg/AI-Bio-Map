```mermaid
flowchart TD
    A["🧬 AI BIO"]

    A --> B["① DATA<br>DATA 생성"]
    A --> C["② AI<br>AI / 모델링"]
    A --> D["③ APPLICATION<br>실제 적용"]

    %% DATA
    B --> B1["🧬 유전체"]
    B --> B2["🧫 세포"]
    B --> B3["🧪 단백질"]

    B1 --> B11["$ILMN"]
    B1 --> B12["$PACB"]
    B1 --> B13["$ONT🇬🇧"]

    B2 --> B21["$TXG"]

    B3 --> B31["$SEER"]
    B3 --> B32["$QSI"]

    %% AI
    C --> C1["🔬 모델링"]
    C --> C2["💊 신약 발견"]
    C --> C3["🧬 합성생물학"]

    C1 --> C11["$SDGR"]

    C2 --> C21["$RXRX"]
    C2 --> C22["$ABCL"]
    C2 --> C23["$ABSI"]
    C2 --> C24["$RLAY"]

    C3 --> C31["$DNA"]
    C3 --> C32["$LTRN"]

    %% APPLICATION
    D --> D1["🩺 진단"]
    D --> D2["🏥 임상"]
    D --> D3["🏭 제조"]

    D1 --> D11["$TEM"]
    D1 --> D12["$GH"]
    D1 --> D13["$NTRA"]

    D2 --> D21["정밀의료"]
    D2 --> D22["환자 데이터"]
    D2 --> D23["임상시험"]

    D3 --> D31["바이오 제조"]
    D3 --> D32["세포·유전자 치료"]

    %% FLOW
    B -.->|"생물학적 데이터"| C
    C -.->|"예측 · 설계"| D
