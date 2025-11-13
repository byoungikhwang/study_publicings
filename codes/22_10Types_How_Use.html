<!DOCTYPE html>
<!-- Chosen Palette: NeoStream Dark Indigo -->
<!-- Application Structure Plan: 2단 그리드 레이아웃(데스크톱 기준)을 설계했습니다. 좌측(lg:col-span-2)에는 핵심 콘텐츠인 '영상 플레이어'와 '데이터 테이블'을 배치하여 시청과 정보 확인을 동시에 가능하게 했습니다. 우측(lg:col-span-1)에는 '승인/반려 컨트롤'과 '타임스탬프 댓글' 등 모든 인터랙션 요소를 집중 배치했습니다. 이 구조는 기획팀의 '직관적인 UI' 요구를 충족하며, 사용자가 시청(좌)과 행동(우)을 명확히 구분하여 사용할 수 있도록 유도합니다. -->
<!-- Visualization & Content Choices: [영상 플레이어 영역 -> Goal: Inform -> Mockup Box (HTML/Tailwind) -> Interaction: None (Mockup) -> Justification: 핵심 기능 시각화 -> Library/Method: HTML/Tailwind], [승인/반려 버튼 -> Goal: Interact -> Buttons (HTML/Tailwind) -> Interaction: Click (JS) -> Justification: 핵심 의사결정 기능 -> Library/Method: JS], [타임스탬프 댓글 -> Goal: Interact/Inform -> Form & List (HTML/Tailwind) -> Interaction: Submit (JS) -> Justification: 핵심 리뷰 기능 -> Library/Method: JS], [데이터 테이블 -> Goal: Inform -> Table (HTML/Tailwind) -> Interaction: Read -> Justification: 운영팀 '데이터 밀집형' 요구 충족 -> Library/Method: HTML/Tailwind] -->
<!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>네오스트림 영상 리뷰 및 승인 대시보드 (프로토타입)</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            @apply bg-gray-900 text-gray-100;
        }
        .custom-scroll::-webkit-scrollbar {
            width: 8px;
        }
        .custom-scroll::-webkit-scrollbar-thumb {
            background-color: #4a5568; 
            border-radius: 10px;
        }
        .custom-scroll::-webkit-scrollbar-track {
            background-color: #1a202c; 
        }
        #toast-container {
            position: fixed;
            bottom: 20px;
            right: 20px;
            z-index: 1000;
        }
    </style>
</head>
<body class="dark">
    <div class="min-h-screen p-4 md:p-8">
        <header class="mb-6 border-b border-gray-700 pb-4">
            <h1 class="text-3xl font-bold text-indigo-400">네오스트림 콘텐츠 승인 대시보드</h1>
            <p class="text-gray-400 mt-1">프로젝트 코드: NS-2025-Q4-01-DRAFT (긴급 프로토타입)</p>
        </header>

        <main class="grid grid-cols-1 lg:grid-cols-3 gap-6">

            <section class="lg:col-span-2 space-y-6">
                <div class="p-6 bg-gray-800 rounded-xl shadow-lg">
                    <h2 class="text-xl font-semibold mb-4 text-white">핵심 콘텐츠 영역</h2>
                    <p class="text-gray-400 mb-6 text-sm">이 영역은 영상 콘텐츠를 직접 확인하고 관련 데이터를 검토하는 공간입니다. 좌측에는 플레이어가, 하단에는 운영팀의 요청을 반영한 데이터 테이블이 위치합니다.</p>
                </div>

                <div class="bg-gray-800 rounded-xl shadow-2xl p-4">
                    <h2 id="video-title" class="text-xl font-semibold mb-3 text-white">영상 제목: 신규 드라마 '환영의 도시' 최종본 리뷰</h2>
                    <div class="aspect-video bg-black rounded-lg flex items-center justify-center border border-gray-700">
                        <div class="text-2xl text-white/50">🎥 Video Player Area (03:45 / 12:30)</div>
                    </div>
                    <div class="mt-3 flex items-center justify-between text-sm text-gray-400">
                        <span>현재 시간: <span id="current-video-time" class="font-mono text-indigo-300">00:00</span></span>
                        <span>요청자: 김PD | 요청일: 2025-11-13</span>
                    </div>
                </div>

                <div class="bg-gray-800 rounded-xl shadow-lg p-6">
                    <h2 class="text-xl font-semibold mb-4 text-indigo-300">영상 상세 메타데이터 및 리뷰 히스토리</h2>
                    <div class="overflow-x-auto rounded-lg border border-gray-700">
                        <table class="min-w-full divide-y divide-gray-700 text-sm">
                            <thead class="bg-gray-700">
                                <tr>
                                    <th class="px-4 py-2 text-left font-medium text-gray-300">항목</th>
                                    <th class="px-4 py-2 text-left font-medium text-gray-300">값</th>
                                    <th class="px-4 py-2 text-left font-medium text-gray-300">최종 수정</th>
                                </tr>
                            </thead>
                            <tbody class="divide-y divide-gray-700 bg-gray-800">
                                <tr>
                                    <td class="px-4 py-2 font-medium text-white">영상 ID</td>
                                    <td class="px-4 py-2 text-gray-300 font-mono">NEO-25Q4-HD-1234</td>
                                    <td class="px-4 py-2 text-gray-400">2025-11-01</td>
                                </tr>
                                <tr>
                                    <td class="px-4 py-2 font-medium text-white">최종 해상도</td>
                                    <td class="px-4 py-2 text-gray-300">4K (3840x2160)</td>
                                    <td class="px-4 py-2 text-gray-400">2025-11-10</td>
                                </tr>
                                <tr>
                                    <td class="px-4 py-2 font-medium text-white">리뷰 상태</td>
                                    <td class="px-4 py-2"><span id="approval-status" class="inline-flex items-center rounded-full bg-yellow-500/20 px-2 py-0.5 text-xs font-medium text-yellow-300">검토 대기 중</span></td>
                                    <td class="px-4 py-2 text-gray-400">-</td>
                                </tr>
                                <tr>
                                    <td class="px-4 py-2 font-medium text-white">리뷰 횟수</td>
                                    <td class="px-4 py-2 text-gray-300">3회</td>
                                    <td class="px-4 py-2 text-gray-400">2025-11-13</td>
                                </tr>
                            </tbody>
                        </table>
                    </div>
                </div>
            </section>

            <section class="lg:col-span-1 space-y-6">
                <div class="p-6 bg-gray-800 rounded-xl shadow-lg">
                    <h2 class="text-xl font-semibold mb-4 text-white">리뷰 및 승인 영역</h2>
                    <p class="text-gray-400 mb-6 text-sm">이 영역은 영상 리뷰의 핵심인 '의사 결정'과 '의견 교환'을 담당합니다. 최종 승인/반려를 결정하고, 타임스탬프와 함께 구체적인 피드백을 남길 수 있습니다.</p>
                </div>

                <div class="bg-gray-800 rounded-xl shadow-2xl p-6 border border-gray-700">
                    <h2 class="text-xl font-semibold mb-4 text-white">최종 승인/반려 결정</h2>
                    <div class="flex space-x-4">
                        <button id="btn-approve" class="flex-1 py-3 rounded-xl font-bold text-white transition duration-200 bg-green-600 hover:bg-green-700 shadow-lg hover:shadow-green-500/50">
                            ✅ 승인 (Approve)
                        </button>
                        <button id="btn-reject" class="flex-1 py-3 rounded-xl font-bold text-white transition duration-200 bg-red-600 hover:bg-red-700 shadow-lg hover:shadow-red-500/50">
                            ❌ 반려 (Reject)
                        </button>
                    </div>
                    <p class="text-xs text-gray-500 mt-3 text-center">결정된 상태는 실시간으로 반영됩니다.</p>
                </div>

                <div class="bg-gray-800 rounded-xl shadow-2xl p-6">
                    <h2 class="text-xl font-semibold mb-4 text-indigo-300">타임스탬프 리뷰 댓글</h2>

                    <div class="mb-4 space-y-2">
                        <textarea id="comment-input" rows="3" placeholder="리뷰 내용을 입력하세요. (예: 2분 30초에 컷 변경 필요)" class="w-full rounded-lg bg-gray-700 border-gray-600 text-gray-100 p-3 placeholder-gray-400 focus:ring-indigo-500 focus:border-indigo-500 transition duration-150"></textarea>
                        <button id="add-comment-btn" class="w-full py-2 rounded-lg font-semibold text-gray-900 bg-indigo-400 hover:bg-indigo-500 transition duration-200 shadow-md">
                            💬 현재 시간에 댓글 추가 (<span id="btn-current-time">00:00</span>)
                        </button>
                    </div>

                    <div id="comment-list" class="space-y-3 h-96 custom-scroll overflow-y-auto pr-2">
                        <div class="p-3 bg-gray-700 rounded-lg border-l-4 border-indigo-500">
                            <div class="flex justify-between items-center text-xs mb-1">
                                <span class="font-semibold text-indigo-300">01:05</span>
                                <span class="text-gray-400">시스템 관리자</span>
                            </div>
                            <p class="text-sm text-gray-200">배경 음악이 너무 큽니다. 믹싱 레벨 조정이 필요해 보입니다.</p>
                        </div>
                        <div class="p-3 bg-gray-700 rounded-lg border-l-4 border-yellow-500">
                            <div class="flex justify-between items-center text-xs mb-1">
                                <span class="font-semibold text-yellow-300">02:30</span>
                                <span class="text-gray-400">디자인팀 조언</span>
                            </div>
                            <p class="text-sm text-gray-200">해당 컷의 색감이 다크 모드 화면에서 다소 묻힙니다. 명도를 살짝 올려주세요.</p>
                        </div>
                    </div>
                </div>

            </section>
        </main>
    </div>

    <div id="toast-container"></div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const TIME_INTERVAL_MS = 1000; 
            let virtualTimeSeconds = 0;
            let isPlaying = true; 

            const timeDisplay = document.getElementById('current-video-time');
            const btnTimeDisplay = document.getElementById('btn-current-time');
            const statusElement = document.getElementById('approval-status');
            const commentInput = document.getElementById('comment-input');
            const commentList = document.getElementById('comment-list');
            const addCommentBtn = document.getElementById('add-comment-btn');
            const btnApprove = document.getElementById('btn-approve');
            const btnReject = document.getElementById('btn-reject');

            function formatTime(totalSeconds) {
                const minutes = Math.floor(totalSeconds / 60);
                const seconds = totalSeconds % 60;
                return `${String(minutes).padStart(2, '0')}:${String(seconds).padStart(2, '0')}`;
            }

            setInterval(() => {
                if (isPlaying) {
                    virtualTimeSeconds++;
                    const formattedTime = formatTime(virtualTimeSeconds);
                    if(timeDisplay) timeDisplay.textContent = formattedTime;
                    if(btnTimeDisplay) btnTimeDisplay.textContent = formattedTime;
                }
            }, TIME_INTERVAL_MS);

            if(btnApprove) {
                btnApprove.addEventListener('click', () => {
                    showToast('✅ 영상이 최종 **승인**되었습니다. 다음 단계로 이동합니다.', 'bg-green-600');
                    if(statusElement) statusElement.innerHTML = '<span class="inline-flex items-center rounded-full bg-green-500/20 px-2 py-0.5 text-xs font-medium text-green-300">최종 승인 완료</span>';
                    isPlaying = false;
                });
            }

            if(btnReject) {
                btnReject.addEventListener('click', () => {
                    showToast('❌ 반려 사유를 댓글로 남겨주세요. 상태가 **반려**로 변경됩니다.', 'bg-red-600');
                    if(statusElement) statusElement.innerHTML = '<span class="inline-flex items-center rounded-full bg-red-500/20 px-2 py-0.5 text-xs font-medium text-red-300">반려</span>';
                    isPlaying = false;
                });
            }

            if(addCommentBtn) {
                addCommentBtn.addEventListener('click', () => {
                    const commentText = commentInput.value.trim();
                    if (commentText === '') {
                        showToast('댓글 내용을 입력해주세요.', 'bg-yellow-600');
                        return;
                    }

                    const currentTime = formatTime(virtualTimeSeconds);
                    const newComment = document.createElement('div');
                    newComment.className = 'p-3 bg-gray-700 rounded-lg border-l-4 border-indigo-500'; 
                    newComment.innerHTML = `
                        <div class="flex justify-between items-center text-xs mb-1">
                            <span class="font-semibold text-indigo-300">${currentTime}</span>
                            <span class="text-gray-400">프론트엔드 개발자 (나)</span>
                        </div>
                        <p class="text-sm text-gray-200">${commentText.replace(/\n/g, '<br>')}</p>
                    `;

                    if(commentList) commentList.prepend(newComment);
                    if(commentInput) commentInput.value = ''; 
                    showToast('💬 타임스탬프 댓글이 추가되었습니다.', 'bg-indigo-600');
                });
            }

            function showToast(message, colorClass = 'bg-gray-600') {
                const container = document.getElementById('toast-container');
                if (!container) return;

                const toast = document.createElement('div');
                toast.className = `p-4 mt-2 rounded-lg shadow-xl text-white ${colorClass} transition-opacity duration-300 ease-in-out opacity-0 max-w-sm`;
                toast.style.wordBreak = 'break-word';
                toast.innerHTML = message;
                
                container.appendChild(toast);

                setTimeout(() => {
                    toast.classList.remove('opacity-0');
                }, 10);

                setTimeout(() => {
                    toast.classList.add('opacity-0');
                    setTimeout(() => {
                        if (container.contains(toast)) {
                            container.removeChild(toast);
                        }
                    }, 300);
                }, 5000);
            }
        });
    </script>
</body>
</html>