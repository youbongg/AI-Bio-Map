```mermaid
flowchart TD
    A["🧬 AI BIO"]

    A --> B["① DATA<br>데이터를 만든다"]
    A --> C["② AI<br>이해·설계한다"]
    A --> D["③ APPLICATION<br>실제로 쓴다"]

    %% DATA
    B --> B1["🧬 유전체"]
    B --> B2["🧫 세포"]
    B --> B3["🧪 단백질"]

    B1 --> B11["Illumina $ILMN"]
    B1 --> B12["PacBio $PACB"]
    B1 --> B13["Oxford Nanopore $ONT"]

    B2 --> B21["10x Genomics $TXG"]

    B3 --> B31["Seer $SEER"]
    B3 --> B32["Quantum-Si $QSI"]

    %% AI
    C --> C1["🔬 모델링"]
    C --> C2["💊 신약 발견"]
    C --> C3["🧬 합성생물학"]

    C1 --> C11["Schrödinger $SDGR"]

    C2 --> C21["Recursion $RXRX"]
    C2 --> C22["AbCellera $ABCL"]
    C2 --> C23["Absci $ABSI"]
    C2 --> C24["Relay $RLAY"]

    C3 --> C31["Ginkgo Bioworks $DNA"]
    C3 --> C32["Lantern Pharma $LTRN"]

    %% APPLICATION
    D --> D1["🩺 진단"]
    D --> D2["🏥 임상"]
    D --> D3["🏭 제조"]

    D1 --> D11["Tempus AI $TEM"]
    D1 --> D12["Guardant Health $GH"]
    D1 --> D13["Natera $NTRA"]

    D2 --> D21["정밀의료"]
    D2 --> D22["환자 데이터"]
    D2 --> D23["임상시험"]

    D3 --> D31["바이오 제조"]
    D3 --> D32["세포·유전자 치료"]

    %% FLOW
    B -.->|"생물학적 데이터"| C
    C -.->|"예측 · 설계"| D
