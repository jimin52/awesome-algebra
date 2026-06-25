## Ⅰ. 군과 환의 대수적 구조 (1~12)

**01. 함수와 이항연산, 대수적 공리와 대수 구조**
- 단사·전사·전단사 함수의 정의와 성질    
- 이항연산의 정의와 대수적 공리(결합법칙, 교환법칙, 분배법칙)
- 항등원(Identity)과 역원(Inverse)의 정의 및 유일성 증명
- 마그마, 반군(Semigroup), 모노이드(Monoid), 군(Group)의 단계별 공리 체계

**02. 카테시안 곱과 이항관계, 동치관계와 동치류**
- 카테시안 곱(Cartesian Product)의 정의와 집합의 족(Family of sets) 확장
- 이항 관계(Binary Relation)와 동치 관계의 3대 조건(반사율, 대칭율, 추이율)
- 동치류(Equivalence Class)의 정의와 몫집합(Quotient Set)
- 동치관계에 의한 집합의 분할(Partition) 정리와 기본 동형

**03. 부분군, 잉여류(Coset)와 라그랑주 정리**
- 부분군 판정법(Subgroup Criterion: 1-step 및 2-step)
- 순환부분군(Cyclic Subgroup)과 생성원(Generator)
- 좌잉여류(Left Coset)와 우잉여류(Right Coset)의 정의 및 성질
- 라그랑주 정리(Lagrange's Theorem)와 지수(Index), 그 따름정리(위수 관계)

**04. 정규부분군, 몫군과 Well-definedness**
- 정규부분군(Normal Subgroup)의 정의와 동치 조건들 ($gHg^{-1} = H$)
- 몫군(Quotient Group)의 집합적 정의와 군 연산 부여
- 몫군 연산의 웰디파인드네스(Well-definedness) 증명 (왜 정규성이 필수적인가)
- 잉여류 연산을 통한 연산 보존성 검증

**05. 군 준동형사상, Kernel과 동형정리**
- 군 준동형사상(Group Homomorphism)과 동형사상(Isomorphism)의 정의
- 준동형사상의 핵(Kernel)과 상(Image)의 대수적 성질 (Kernel은 항상 정규부분군임)
- 제1 동형정리(First Isomorphism Theorem)의 구조와 사영 사상(Projection)
- 제2, 제3 동형정리와 대응정리(Correspondence Theorem)

**06. 환과 가환환의 공리 체계, 부분환과 행렬환**
- 환(Ring)의 공리(덧셈군, 곱셈 반군, 분배법칙)와 단위원을 갖는 환(Ring with identity)
- 가환환(Commutative Ring)의 공리 체계
- 부분환 판정법(Subring Criterion)
- 비가환환의 대표적 예시로서의 행렬환(Matrix Ring)의 대수적 성질

**07. 영인자, 정역과 체(Field)**
- 영인자(Zero Divisor)와 가역원(Unit)의 정의
- 정역(Integral Domain)의 정의와 곱셈 소거법칙(Cancellation Law) 성립 증명
- 체(Field)의 공리 체계와 성질
- "모든 유한 정역은 체이다" 정리의 증명

**08. 체의 특성수와 유한체**
- 환과 체의 특성수(Characteristic) 정의
- 체의 특성수는 $0$ 또는 소수($p$)뿐임을 증명
- 소체(Prime Field: $\mathbb{Q}$ 또는 $\mathbb{Z}_p$)의 개념
- 유한체(Finite Field/Galois Field)의 표수와 원소의 개수가 항상 $p^n$ 형태임의 기본 원리

**09. 환 준동형사상, Kernel과 아이디얼**
- 환 준동형사상(Ring Homomorphism)의 정의와 성질
- 환 준동형사상의 핵(Kernel)이 갖는 대수적 구조 추적
- 좌/우/양측 아이디얼(Ideal)의 정의 (왜 부분환만으로는 부족한가)
- 원소에 의해 생성된 아이디얼(Generated Ideal)과 주아이디얼(Principal Ideal)

**10. 몫환의 정의와 Well-definedness, 환의 동형정리**
- 아이디얼에 의한 몫환(Quotient Ring)의 정의
- 몫환의 곱셈 연산에 대한 Well-definedness 성립 조건 (아이디얼 조건의 필연성)
- 환의 제1, 제2, 제3 동형정리
- 환의 대응정리(Correspondence Theorem for Rings)

**11. 소 아이디얼과 극대 아이디얼**
- 소 아이디얼(Prime Ideal)의 정의와 몫환이 정역(ID)이 될 동치 조건
- 극대 아이디얼(Maximal Ideal)의 정의와 몫환이 체(Field)가 될 동치 조건
- "모든 극대 아이디얼은 소 아이디얼이다" 성질과 단위원을 갖는 가환환에서의 반례 탐색
- Zorn의 소정리를 이용한 극대 아이디얼의 존재성 증명

**12. 다항식환과 주이상역(PID)**
- 가환환 위의 다항식환 $R[x]$의 정의와 차수(Degree)의 성질
- 체 위의 다항식환 $F[x]$에서의 나눗셈 정리(Division Algorithm)
- 유클리드 정역(ED), 주이상역(PID), 유일인수분해정역(UFD)의 정의와 포함 관계 ($ED \implies PID \implies UFD$)
- $F[x]$가 PID가 됨의 증명

## Ⅱ. 선형대수학의 대수적 기초 (13~21)

**13. 벡터공간, 부분공간과 생성(Span)**
- 체 $F$ 위의 벡터공간(Vector Space)의 8대 공리 체계
- 부분공간 판정법(Subspace Criterion)
- 일차결합(Linear Combination)과 선형 생성(Span)의 정의 및 부분공간성

**14. 선형독립, 기저와 차원**
- 선형독립(Linear Independence)과 선형종속(Linear Dependence)의 정의와 판정
- 기저(Basis)의 정의(선형독립 + Span)
- 유한차원 벡터공간의 기저 원소 개수의 유일성 증명
- 차원(Dimension)의 정의와 차원 정리 ($\dim(W_1 + W_2)$)

**15. 선택공리, Zorn의 소정리와 기저 존재정리**
- 선택공리(Axiom of Choice)와 Zorn의 소정리(Zorn's Lemma)의 서술과 동치성 인정
- 극대 선형독립 집합의 존재성 추적
- 하우스도르프 극대원리를 이용한 "모든 벡터공간(무한차원 포함)은 기저를 갖는다"의 증명

**16. 선형사상, Kernel과 Image**
- 선형사상(Linear Map/Transformation)의 정의
- 선형사상의 핵(Kernel/Null Space)과 상(Image/Range)의 부분공간성 증명
- 선형사상의 단사(Injective) 조건이 $\ker(T) = {0}$임의 동치 증명

**17. 선형사상 공간, 행렬 표현과 기저변환**
- 선형사상들의 집합 $\mathcal{L}(V,W)$의 벡터공간 구조와 차원
- 순서기저(Ordered Basis)의 도입과 선형사상의 행렬 표현(Matrix Representation)
- 기저변환 행렬(Transition Matrix)의 유도와 좌표벡터의 변환 규칙
- 선형연산자의 닮음(Similarity) 정의와 불변량

**18. 몫공간, Rank-Nullity 정리와 제1 동형정리**
- 벡터공간의 부분공간에 의한 몫공간(Quotient Space) $V/W$과 덧셈/스칼라곱 공리
- 몫공간의 차원 정리 ($\dim(V/W) = \dim V - \dim W$)
- 몫공간 구조를 활용한 랭크-선nullity 정리(Rank-Nullity Theorem)의 대수적 증명
- 벡터공간 버전의 제1 동형정리

**19. 고유값, 고유벡터와 특성다항식**
- 고유값(Eigenvalue), 고유벡터(Eigenvector), 고유공간(Eigenspace)의 정의
- 특성다항식(Characteristic Polynomial) $\det(T - \lambda I)$의 정의와 닮음 불변성
- 대수적 중복도(Algebraic Multiplicity)의 정의

**20. 최소다항식, Cayley-Hamilton 정리와 순환부분공간**
- 연산자를 영공간으로 보내는 다항식 아이디얼과 최소다항식(Minimal Polynomial)의 유일한 정의
- 케일리-해밀턴 정리(Cayley-Hamilton Theorem)의 대수적 증명
- $T$-순환부분공간(T-cyclic Subspace)의 정의와 companion matrix 유도 기초

**21. 대각화 가능성과 대각화 정리**
- 기하적 중복도(Geometric Multiplicity)의 정의 및 대수적 중복도와의 대소 관계 증명
- 선형연산자가 대각화 가능(Diagonalizable)할 동치 조건 정리
- 서로 다른 고유값에 대응하는 고유벡터들의 선형독립성 증명과 대각화 정리

## Ⅲ. 내적공간과 스펙트럼 정리 (22~30)

**22. 내적공간, 노름과 거리**
- 실내적 및 복소내적(Inner Product)의 공리 체계(양의 정부호성, 선형성, 켤레대칭성)
- 코시-슈바르츠 부등식(Cauchy-Schwarz Inequality)과 삼각부등식 증명
- 내적으로부터 유도되는 노름(Norm)과 거리(Metric)의 대수적·해석학적 구조

**23. 직교성, 직교여공간과 직교기저**
- 직교(Orthogonality)와 정규직교(Orthonormality)의 정의
- 직교집합의 선형독립성 증명
- 부분공간의 직교여공간(Orthogonal Complement) $W^\perp$의 정의와 성질 ($V = W \oplus W^\perp$)

**24. Gram-Schmidt 직교화, 직교투영과 최소제곱문제**
- 그람-슈미트 직교화 과정(Gram-Schmidt Orthogonalization) 알고리즘과 기저 존재성
- 직교투영(Orthogonal Projection) 연산자의 정의와 최적 근사 정리(Best Approximation)
- 부적합 연립방정식의 최소제곱문제(Least Squares Problem)와 정규방정식($A^*Ax = A^*b$) 유도

**25. 수반사상, 정규연산자와 자기수반연산자**
- 리스 표현 정리(Riesz Representation Theorem)의 유한차원 버전
- 수반사상(Adjoint Operator) $T^*$의 정의와 행렬 표현(켤레전치)
- 정규연산자($TT^* = T^*T$)와 자기수반연산자(Self-adjoint/Hermitian, $T = T^*$)의 정의와 기초 성질

**26. 유니타리 연산자와 스펙트럼 정리**
- 유니타리 연산자(Unitary/Orthogonal, $T^* = T^{-1}$)의 정의와 등거리 사상(Isometry) 특성
- "복소 내적공간 위에서 연산자가 정규연산자일 동치조건은 정규직교 고유벡터 기저를 갖는 것이다" (복소 스펙트럼 정리)
- 슈어 정리를 이용한 정규연산자의 유니타리 삼각화 및 대각화 가능성 증명

**27. 직교대각화, 실대칭행렬과 복소정규행렬**
- 실자기수반연산자(실대칭행렬)의 고유값은 항상 실수임의 증명
- 실대칭행렬의 스펙트럼 정리 (직교행렬에 의한 대각화 가능성)
- 복소정규행렬의 유니타리 대각화 실전 구조

**28. Positive Semi-Definite 연산자와 Polar Decomposition**
- 양의 반정치(Positive Semi-definite) 및 양의 정부호(Positive Definite) 연산자의 고유값 및 내적 정의
- 연산자의 제곱근(Square Root of an operator)의 유일한 존재성 증명
- 임의의 선형연산자를 $T = UP$ ($U$는 유니타리, $P$는 Positive semi-definite) 형태로 쪼개는 극분해(Polar Decomposition) 정리

**29. Singular Value, Moore-Penrose Pseudoinverse와 SVD**
- 임의의 선형사상에 대한 특이값(Singular Value)의 정의 ($\sqrt{T^*T}$의 고유값)
- 직각행렬 및 임의의 선형사상의 특이값 분해(SVD: Singular Value Decomposition) 기하학적·대수적 정립
- 무어-펜로즈 의사역행렬(Moore-Penrose Pseudoinverse)의 대수적 조건 4가지와 SVD를 통한 구조적 구축

**30. Low-Rank Approximation**
- 행렬 노름(Frobenius 2-norm 및 Spectral norm)의 정의
- 에카르트-영-미르스키 정리(Eckart-Young-Mirsky Theorem)의 서술과 SVD 커팅을 통한 최적 저랭크 근사행렬 구축
- 주성분 분석(PCA)과의 대수적 연결고리 해설

## Ⅳ. 가군(Module)과 행렬의 표준형 (31~38)

**31. 환 위의 가군(Module), 부분가군과 몫가군**
- 환 $R$ 위의 좌/우 가군(Module)의 공리 체계 (벡터공간의 스칼라를 환으로 확장)
- 가군과 벡터공간의 결정적 차이점 분석 (나눗셈 불가능성, 비가역성)
- 부분가군 판정법(Submodule Criterion)과 몫가군(Quotient Module) $M/N$의 대수 구조

**32. 가군 준동형사상과 자유가군**
- 가군 준동형사상(Module Homomorphism)의 정의와 핵(Kernel), 상(Image)
- 가군의 제1 동형정리
- 자유 가군(Free Module)의 정의와 기저(Basis)의 성질 및 보편 성질(Universal Property)

**33. 기저의 비존재성, 유한생성 가군**
- 자유가군이 아닌 가군의 예시 고찰 (e.g., $\mathbb{Z}$-가군으로서의 유한가환군 $\mathbb{Z}_n$은 기저가 없음)
- 유한생성 가군(Finitely Generated Module)의 정의
- 가군에서는 부분가군이 유한생성이 아닐 수 있음을 인식하고 가환환의 노터성(Noetherian) 맛보기

**34. PID 위 유한생성 가군 구조정리**
- 비틀림 원소(Torsion element)와 비틀림 부분가군(Torsion submodule) $M_{\text{tor}}$
- 주이상역(PID) 위에서 유한생성 가군이 자유 부분과 비틀림 부분의 직합(Direct Sum)으로 쪼개진다는 대정리의 서술
- $M \cong R^r \oplus M_{\text{tor}}$ 형태의 대수적 거동 분석

**35. 불변인자 분해와 초등인자 분해**
- 불변인자 분해(Invariant Factor Decomposition): $M \cong R^r \oplus R/\langle d_1 \rangle \oplus \cdots \oplus R/\langle d_k \rangle$ ($d_1 | d_2 | \cdots | d_k$)
- 중국인의 나머지 정리(CRT)를 이용한 초등인자 분해(Elementary Divisor Decomposition)로의 전환
- 두 분해 방식의 유일성(Uniqueness) 증명 구조

**36. 선형연산자의 F[x]-가군 구조**
- 체 $F$ 위의 벡터공간 $V$와 선형연산자 $T$가 주어졌을 때, 다항식 곱셈 연산 $f(x) \cdot v = f(T)(v)$를 통해 $V$를 $F[x]$-가군으로 빌드업하는 과정
- $V$가 유한차원이므로 $F[x]$-가군으로서 항상 유한생성 비틀림 가군(Finitely generated torsion module)이 됨을 증명

**37. Rational Canonical Form**
- $F[x]$-가군의 불변인자 분해를 체 $F$ 위의 선형대수학 언어로 번역
- 각 불변인자 다항식에 대응하는 동반행렬(Companion Matrix)들의 블록 대각선 행렬 구축
- 임의의 필드 위에서 닮음을 통해 유도되는 유일한 유리스 표준형(Rational Canonical Form) 정의

**38. Jordan Canonical Form과 Jordan 분해**
- $F[x]$-가군의 초등인자 분해를 대수적으로 닫힌 체(C) 또는 일차식으로 쪼개지는 체 위에서 번역
- 고유값과 멱영 연산자(Nilpotent Operator)의 성질을 결합하여 조단 블록(Jordan Block)의 유도
- 최종 조단 표준형(Jordan Canonical Form) 및 연산자를 대각화 가능 부분과 멱영 부분의 합으로 쪼개는 조단 분해($T = D + N$)

## Ⅴ. 다중선형대수학과 텐서 (39~45)

**39. 쌍선형사상, 쌍선형형식과 다중선형사상**
- 쌍선형 사상(Bilinear Map) $B: V \times W \to U$의 정의와 대수적 성질
- 쌍선형 형식(Bilinear Form)의 표현 행렬과 기저 변환 시 합동(Congruence) 관계
- 다중선형 사상(Multilinear Map) $f: V_1 \times \cdots \times V_n \to U$의 일반화 정의

**40. 텐서곱의 정의와 Universal Property**
- 다중선형성을 선형성으로 환원하기 위한 텐서곱(Tensor Product) 공간 $V \otimes W$의 보편 성질(Universal Property) 유도
- 보편 성질에 의한 텐서곱의 유일성(Up to isomorphism) 증명

**41. 텐서곱의 존재성, 유일성과 텐서공간의 구축**
- 곱집합 $V \times W$로부터 생성된 자유 벡터공간(Free Vector Space) $F(V \times W)$ 정의
- 쌍선형성을 강제하는 부분공간 $R$을 정의하고 몫공간 $F(V \times W)/R$로써 텐서곱 공간 구체적 존재 증명
- 기저의 구성 $\{v_i \otimes w_j\}$과 텐서곱 공간의 차원 정리 ($\dim(V \otimes W) = \dim V \times \dim W$)

**42. (r,s)-형 텐서**
- 쌍대공간(Dual Space) $V^*$와 선형형식(Linear Form) 재정립
- 공변(Covariant) $r$계, 반변(Contravariant) $s$계 텐서 공간 $T^r_s(V) = V^{\otimes r} \otimes (V^*)^{\otimes s}$의 정의
- 다중선형사상 공간 $\mathcal{L}(V^_,\dots,V^_, V,\dots,V; F)$과의 자연스러운 동형(Natural Isomorphism) 증명

**43. 대칭 텐서 대수와 교대 텐서 대수**
- 대칭화 연산자(Symmetrizer)와 교대화 연산자(Antisymmetrizer)의 정의 및 성질
- 대칭 텐서 공간 $S^k(V)$와 대칭 텐서 대수(Symmetric Algebra) $S(V)$
- 교대 텐서 공간 $\Lambda^k(V)$의 대수적 정의

**44. 외대수와 쐐기곱(Wedge Product)**
- 외대수(Exterior Algebra) $\Lambda(V) = \bigoplus_{k=0}^{\infty} \Lambda^k(V)$의 대수적 몫공간 정의 ($v \otimes v$ 형태의 원소들로 생성된 아이디얼로 나눔)
- 쐐기곱(Wedge Product, $\wedge$)의 정의와 반대칭성($v \wedge w = -w \wedge v$) 증명
- $\Lambda^k(V)$의 기저 $\{v_{i_1} \wedge \cdots \wedge v_{i_k}\}$ 구성과 차원 정리 $\binom{n}{k}$

**45. 미분형식의 대수적 기초**
- 여접공간의 외대수 원소로서의 외적 형식(Exterior Form) 개념 선행 도입
- 쐐기곱의 기저 변환과 행렬식(Determinant)의 대수적 유도 과정
- 부피 원소(Volume form)의 대수적 뼈대 확립

## Ⅵ. 매끄러운 다양체의 대수적 접근 (46~50)

**46. 매끄러운 다양체**
- 위상다양체(Topological Manifold)의 정의 (Hausdorff + Second Countable)
- 국소 좌표계(Chart)와 아틀라스(Atlas)의 대수적·위상적 정의
- 좌표변환 사상(Transition Map)의 호환성과 매끄러운 다양체($Smooth\ Manifold$) 구조 정의

**47. 다양체 위 함수환**
- 다양체 $M$ 위에서 정의된 매끄러운 실수값 함수들의 집합 $C^\infty(M)$의 정의
- 함수의 점별 덧셈과 곱셈 하에서 $C^\infty(M)$이 단위원을 갖는 거대한 가환환(Commutative Ring)이 됨을 증명
- 국소화(Localization)와 지포함수(Bump Function)의 대수적 성질

**48. 함수환 위의 가군**
- 다양체 위의 매끄러운 벡터장(Vector Fields)의 공간 $\mathcal{X}(M)$ 정의
- 환 $C^\infty(M)$의 스칼라 곱셈 연산을 통해 $\mathcal{X}(M)$이 $C^\infty(M)$-가군(Module) 구조를 가짐을 규명
- 리 괄호(Lie Bracket) 연산과 환 $C^\infty(M)$ 위에서의 대수적 거동

**49. 접공간과 쌍대공간**
- 다양체 위 한 점 $p$에서의 미분 성질(Derivation)들의 집합으로써 접공간 $T_pM$의 순수 대수적 정의
- 대수적 정의와 기하학적 정의(곡선의 속도벡터)의 동치성 증명
- 쌍대공간인 여접공간(Cotangent Space) $T_p^*M$과 점별 외대수 공간 $\Lambda^k(T_p^*M)$의 연결

**50. 벡터다발의 대수적 관점**
- 벡터다발(Vector Bundle) $E \to M$의 정의와 매끄러운 단면(Section) 공간 $\Gamma(E)$의 정의
- 단면 공간 $\Gamma(E)$가 환 $C^\infty(M)$ 위에서 유한생성 사영 가군(Finitely Generated Projective Module)이 됨을 고찰
- 기하학적 대상(벡터다발)과 대수학적 대상(사영 가군) 사이의 동치를 말하는 세르-스완 정리(Serre-Swan Theorem)의 개념적 완결

