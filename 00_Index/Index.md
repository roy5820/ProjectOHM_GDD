# 🗂️ NOVA – Master Index
> 모든 핵심 문서를 한눈에 보고, 어디서든 1-클릭으로 이동할 수 있는 대시보드야.  
> **Tip** : 각 섹션 첫 줄에 `[[00_Index/Index]]` 링크를 달아두면 언제든 홈으로 돌아올 수 있어!

## 📌 Quick Jump
- 🏠 [[01_Game_Overview/Game_Overview|게임 개요]]
- 🎮 [[02_Core_Gameplay/Core_Loop|핵심 게임플레이]]
- 🌍 [[03_Story_Setting/Main_Story_Arc|세계관·스토리]]
- 🧑‍🚀 [[04_Characters/PC_Rex|플레이어 캐릭터]]
- ⚙️ [[05_Game_Systems/Combat_System|게임 시스템]]
- 🗺️ [[06_Level_World/Level_S1_HiveTower|레벨 디자인]]
- 🎨 [[07_Art_Bible/Color_Palette|아트 바이블]]
- 🔊 [[08_Audio/Music_Style|오디오]]
- 🛠️ [[09_Technical/Build_Pipeline|테크 노트]]
- 📅 [[10_Production/Milestones|프로덕션]]
- 🐞 [[11_QA/Bug_Tracker|QA / 버그]]

---

## 1️⃣ Game Overview
| 문서 | 설명 |
| --- | --- |
| [[01_Game_Overview/Game_Overview]] | 게임 타이틀·장르·USP 한눈에 |
| [[01_Game_Overview/Vision_Goals]] | 비전·완성 정의(DoD) |

## 2️⃣ Core Gameplay
| 문서 | 설명 |
| --- | --- |
| [[02_Core_Gameplay/Controls]] | 입력 스킴·UI 툴팁 |
| [[02_Core_Gameplay/Core_Loop]] | 1분·10분 루프 다이어그램 |

## 3️⃣ Story & Setting
| 문서 | 설명 |
| --- | --- |
| [[03_Story_Setting/World_Timeline]] | ‘노바 사태’ 연표 |
| [[03_Story_Setting/Main_Story_Arc]] | 챕터 플롯 요약 |

## 4️⃣ Characters
| 문서 | 설명 |
| --- | --- |
| [[04_Characters/PC_Rex]] | Rex 스탯·배경 |
| [[04_Characters/PC_Vera]] | Vera 스탯·배경 |
| [[04_Characters/PC_Ion]] | Ion 스탯·배경 |
| [[04_Characters/Boss_Salum]] | 보스 Salum 패턴 |

## 5️⃣ Game Systems
| 문서 | 설명 |
| --- | --- |
| [[05_Game_Systems/Combat_System]] | 기본/강공/패링 로직 |
| [[05_Game_Systems/Switch_System]] | 팀 스위치 메커닉 |
| [[05_Game_Systems/Piktos_System]] | 픽토스 슬롯·코스트 |
| [[05_Game_Systems/Difficulty]] | 난이도 배율·보상 |

## 6️⃣ Level & World
| 문서 | 설명 |
| --- | --- |
| [[06_Level_World/Level_S1_HiveTower]] | S-1 플로우 |
| [[06_Level_World/Level_S2_Rowline]] | S-2 플로우 |
| [[06_Level_World/Level_S3_RedStrip]] | S-3 플로우 |

## 7️⃣ Art Bible
| 문서 | 설명 |
| --- | --- |
| [[07_Art_Bible/Color_Palette]] | 흑백+선홍 팔레트 |
| [[07_Art_Bible/UI_Guidelines]] | HUD·폰트·아이콘 규칙 |

## 8️⃣ Audio
| 문서 | 설명 |
| --- | --- |
| [[08_Audio/Music_Style]] | BGM 방향·참고곡 |
| [[08_Audio/SFX_Catalog]] | SFX 목록·출처 |

## 9️⃣ Technical
| 문서 | 설명 |
| --- | --- |
| [[09_Technical/Shader_BW]] | 흑백 셰이더 그래프 |
| [[09_Technical/Build_Pipeline]] | Git·빌드 스크립트 |

## 🔟 Production
| 문서 | 설명 |
| --- | --- |
| [[10_Production/Milestones]] | 6개월 마일스톤 |
| [[10_Production/Backlog_Kanban]] | 작업 칸반 |
| [[10_Production/Risk_Register]] | 리스크 매트릭스 |

## 1️⃣1️⃣ QA
| 문서 | 설명 |
| --- | --- |
| [[11_QA/Playtest_Reports]] | 플레이테스트 로그 |
| [[11_QA/Bug_Tracker]] | 버그 & 재현 단계 |

---

## 🗒️ Dataview 빠른 목록 (예시)
```dataview
table file.link as "최근 수정 문서", file.mtime
from ""
where file.folder != "99_Archive"
sort file.mtime desc
limit 10
