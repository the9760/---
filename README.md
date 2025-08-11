
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>슈퍼바이브 게임 분석서</title>
    <!-- Inter Font -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d1117;
            color: #e2e8f0;
        }
        .container {
            max-width: 960px;
            margin: auto;
        }
        .card {
            background-color: #1a202c;
            border-radius: 0.5rem;
            padding: 1.5rem;
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        .section-title {
            color: #63b3ed;
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 1rem;
            border-bottom: 2px solid #63b3ed;
            padding-bottom: 0.5rem;
        }
        .list-disc-custom li {
            position: relative;
            padding-left: 1.5rem;
        }
        .list-disc-custom li::before {
            content: '';
            position: absolute;
            left: 0;
            top: 0.75rem;
            width: 8px;
            height: 8px;
            background-color: #63b3ed;
            border-radius: 50%;
        }
    </style>
</head>
<body class="bg-gray-900 p-8">

    <div class="container space-y-8">

        <!-- Header Section -->
        <header class="text-center p-6 card">
            <h1 class="text-4xl font-bold text-white mb-2">슈퍼바이브 게임 분석서</h1>
            <p class="text-lg text-gray-400">넥슨게임즈 지원 목적</p>
        </header>

        <!-- Main Content -->
        <main class="space-y-8">

            <!-- Overview Section -->
            <section class="card">
                <h2 class="section-title">1. 개요</h2>
                <div class="grid grid-cols-1 md:grid-cols-2 gap-4 text-gray-300">
                    <div>
                        <p class="font-bold text-white">게임명:</p>
                        <p>슈퍼바이브 (Supervive)</p>
                    </div>
                    <div>
                        <p class="font-bold text-white">장르:</p>
                        <p>MOBA + 배틀로얄</p>
                    </div>
                    <div>
                        <p class="font-bold text-white">개발사:</p>
                        <p>Theorycraft games</p>
                    </div>
                    <div>
                        <p class="font-bold text-white">출시일:</p>
                        <p>2025. 7. 24.</p>
                    </div>
                </div>
            </section>

            <!-- Game Play Analysis Section -->
            <section class="card">
                <h2 class="section-title">2. 게임 플레이 분석</h2>
                <div class="space-y-4">
                    <div>
                        <h3 class="text-lg font-bold text-white">게임 플레이 방식</h3>
                        <p class="mt-1 text-gray-300">스쿼드(3인) 팀 구성 전장 진입 → 사냥 및 플레이어 처치(재화 획득) → 아이템 구매 → 최후의 생존 팀 승리</p>
                    </div>
                    <div>
                        <h3 class="text-lg font-bold text-white">게임 플레이 특징</h3>
                        <ul class="list-disc-custom pl-4 mt-1 space-y-2 text-gray-300">
                            <li>쿼터뷰 방식의 전투로 시야 확보와 전략적 움직임이 중요합니다.</li>
                            <li>아이템 및 맵 요소 랜덤화로 높은 전략성을 유도합니다.</li>
                            <li>전투 중심의 파밍 구조로 능동적인 교전 플레이가 가능합니다.</li>
                            <li>지형을 이용한 전투로 역전의 가능성을 높입니다.</li>
                        </ul>
                    </div>
                </div>
            </section>

            <!-- BM & Graphics Section -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <section class="card">
                    <h2 class="section-title">3. BM 분석</h2>
                    <div class="space-y-4">
                        <p class="text-gray-300">
                            게임은 무료로 플레이 가능하지만 캐릭터 번들, 스킨, 배틀패스 등 다양한 상품이 존재합니다.
                        </p>
                        <p class="text-gray-300">
                            인게임 재화(프리즈마)로는 대장간에서 장착 아이템 구매 및 뽑기가 가능합니다.
                        </p>
                    </div>
                </section>
                <section class="card">
                    <h2 class="section-title">4. 그래픽 & 아트 스타일</h2>
                    <div class="space-y-4">
                        <p class="text-gray-300">
                            슈퍼바이브만의 쿼터뷰 전투 표현 및 화려한 스킬 이펙트가 특징입니다.
                        </p>
                        <p class="text-gray-300">
                            쿼터뷰 형식의 타사 게임 (이터널 리턴) 비해 다양한 컬러톤과 카툰적 일러스트를 사용하고 있다고 생각합니다.
                        </p>
                    </div>
                </section>
            </div>

            <!-- Sound and Production Section -->
            <section class="card">
                <h2 class="section-title">5. 사운드 및 연출</h2>
                <div class="space-y-4">
                    <p class="text-gray-300">
                        전투 시의 긴장감 높은 연출과 도파민 넘치는 속도감을 강조합니다.
                    </p>
                    <ul class="list-disc-custom pl-4 mt-1 space-y-2 text-gray-300">
                        <li>전투 사운드를 통해 근처 적의 위치를 파악하고, 전략적인 게임 플레이가 가능합니다.</li>
                        <li>상대 플레이어 처치 시 발생하는 사운드는 성취감을 주어 더욱 몰입감 있는 플레이를 유도합니다.</li>
                    </ul>
                </div>
            </section>

            <!-- Comparison Section -->
            <section class="card">
                <h2 class="section-title">6. 경쟁 게임과 비교</h2>
                <div class="space-y-4">
                    <p class="text-gray-300">
                        대표적으로 <span class="text-white font-bold">"이터널리턴"</span>과 비교할 수 있습니다. <br>
                    </p>두 게임 모두 쿼터뷰 시점의 배틀로얄 방식을 채택하고 있으며, 소규모 팀 전투가 핵심인 구조를 가지고 있습니다. <br>

"이터널리턴"은 아이템을 제작하며 전투를 준비하는 방식으로, 강력한 장비를 갖추기까지 상대적으로 시간이 더 소요됩니다.<br> 반면, 슈퍼바이브는 미니언 및 적 플레이어(헌터)를 처치해 재화를 획득하고, 이 재화로 아이템을 직접 구매하는 방식이기 때문에, 초반부터 전투를 통해 빠르게 성장할 수 있다는 차별점이 있습니다.
직접 플레이하면서 느낀 단점은 신규 유저에게 다소 진입장벽이 있다고 생각합니다. <br> 예를 들어, 아이템은 메인화면 > 대장간 > 제작소에서 미리 구매하거나 뽑기를 통해 아이템을 보유하고 있어야 인게임에서 구매할 수 있습니다. <br>하지만 처음 플레이하는 유저는 기본 아이템만 보유한 채 시작하게 되며, 반면 기존 유저는 이미 상위 아이템을 등록해두었기 때문에 더 강력한 장비를 바로 구매할 수 있습니다.<br>
이러한 차이로 인해, 신규 유저는 상대 유저를 반드시 처치해야 상위 아이템을 획득할 수 있는데, 초반 숙련도가 낮은 상태에서는 전투에서 이기기 어려운 구조일 수 있습니다. <br>물론 슈퍼바이브는 3:3 팀 기반 게임이므로 팀의 도움으로 승리할 수 있지만, 자신의 기여도가 낮다고 느낄 경우, 게임의 재미를 충분히 느끼지 못하거나 흥미를 잃을 가능성도 있다고 생각됩니다.

                    <div class="p-4 rounded-lg bg-red-900 bg-opacity-30 border border-red-700">
                        <p class="font-bold text-red-400">단점:</p>
                        <p class="text-gray-300 mt-1">
                            신규 유저에게 진입장벽이 있습니다. 기존 유저는 상위 아이템을 등록해두고 시작할 수 있는 반면, 신규 유저는 기본 아이템만 보유한 채 시작하기 때문입니다.
                        </p>
                    </div>
                </div>
            </section>

            <!-- Improvements and Suggestions Section -->
            <section class="card">
                <h2 class="section-title">7. 개선점 및 제안</h2>
                <div class="space-y-4">
                    <p class="text-lg font-bold text-yellow-400">문제점: 신규 유저 유입을 위한 진입 장벽 해소 및 가이드 시스템 부족</p>
                    <div class="space-y-2">
                        <h3 class="text-lg font-bold text-white">제안: 신규 유저 가이드 시스템 강화</h3>
                        <ul class="list-disc-custom pl-4 mt-1 space-y-2 text-gray-300">
                            <li><span class="font-bold text-white">캐릭터별 추천 아이템 세팅 강조:</span> 신규 유저들이 쉽게 볼 수 있도록 추천 아이템 표시를 더 강조해야 합니다.</li>
                            <li><span class="font-bold text-white">스탯 및 스킬 성장 가이드:</span> 우선적으로 장착해야 할 아이템이나 추천 스킬에 하이라이트를 표시하여 직관적인 성장 경로를 제공해야 합니다.</li>
                            <li><span class="font-bold text-white">스킬 콤보 및 상세 안내:</span> 초보자를 위한 기본 콤보, 전투 팁, 운영 방식을 영상 또는 튜토리얼 형태로 제공하는 것이 좋습니다.</li>
                        </ul>
                    </div>
                    <div class="mt-4">
                        <p class="text-gray-300">
                            또한, 커스텀 모드, 이벤트 맵, 합체 스킬 등 전투적 재미 요소를 추가하면 신규 유저뿐만 아니라 기존 유저에게도 신선한 콘텐츠 경험을 제공하여 커뮤니티 활성화 및 자연스러운 홍보 효과를 기대할 수 있습니다.
                        </p>
                    </div>
                </div>
            </section>

        </main>
    </div>

</body>
</html>
