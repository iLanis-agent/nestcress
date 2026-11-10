# Nestcress 1.0 TEST
Native Android Oyakodori family-routing puzzle. Android 8+ (min26), target35. Package com.gg007.nestcress. Twelve original unique boards on a 4x3 grid.

## Rules
Oyakodori on a 4x3 grid with two outlined rooms, two white adults, two black chicks and two separate two-cell gold nests. Draw orthogonal paths from every bird to a nest cell. Paths cannot share cells, cross, branch, loop or pass through other birds. A path stops at its first nest tile and cannot pass through a nest. Each nest receives exactly one adult and one chick in different tiles. White adults must cross at least one room border; black chicks cannot cross any room border. Unused cells are allowed. Tap gaps between neighboring cells to add/remove links. Twelve original uniquely solved room layouts; undo/reset, levels and saved palette/optional room letters. Known Oyakodori adaptation. All nests are used in this compact edition.

## Download and status
https://mega.co.nz/#!5A1xwIoI!jlc-fwsGKmreQJQsf1aKRJRoLclvJPUNqSOdWC1rtMw
APK SHA256 cd1b2dbf55b82d3bedf31e0e467c7b9fdb5b0f84ca6dc8850eccce1667d0297c; 20974 bytes. Original signing certificate SHA256 1651d9e269ece8a76f36ed4bba24ebc50f9de1e5f856e0567e0e8169fcb25597. Anonymous downloaded bytes match. No requested permissions. Original icon unchanged.

## Checks
Portable seed-761110 generator enumerates all 131,072 edge states and groups legal four-path forests by endpoints. It finds twelve distinct uniquely solved layouts and completions from 19 connected six-cell room partitions in 126 attempts. Independent oracle uses disjoint-set components and counts crossing edges, bird types and nest arrivals; production walks each bird path to its first nest. All 1,572,864 complete edge states plus 120,000 randomized/invalid bird-room-nest cases agree. Bounds, undo/replay/reset and solved lock pass. Actual drawing-adapter edge-midpoint taps solve all twelve and check menu, privacy, levels, next and saved palette/room letters/completion. Seven drawing previews inspected, not phone screenshots. Phone runtime/performance/external-browser QA and full Git source commit remain incomplete. Signed TEST, not final or Play published.

## Functional difference
Reviewed all 207 live studio descriptions and the 803-entry web registry. No functional match for Oyakodori age-based border routing and one-adult/one-chick nest occupancy. Homecress routes matching letters into homes but has no age-specific border rules or two-cell family nests. Birdcress pairs circle endpoints by country counts, without nests or bird types. Nestcress instead routes two adults and two chicks into two-cell nests under opposite border-crossing constraints. Known Oyakodori adaptation; original generated layouts, code and visuals, not a global invention. Six sources cover a rules encyclopedia, a constructor discussion, a competition recap, implementation coverage and puzzle/publisher context. Only the rules encyclopedia governs the standard border behavior; the constructor source is a hybrid, not authority for its altered crossing rules. No source layouts, code or art copied.
Rules https://scrapbox.io/puzzle-pedia/%E3%81%8A%E3%82%84%E3%81%93%E3%81%A9%E3%82%8A ; independent rules https://logic-masters.de/Raetselportal/Raetsel/zeigen.php?chlang=en&id=000M2Y .

## Build
JDK17, Android SDK35/build-tools35.0.0. python generate-levels.py reproduces levels.json. javac -d /tmp/blue-test src/com/gg007/nestcress/Board.java BoardTest.java then java -cp /tmp/blue-test com.gg007.nestcress.NestBoardTest. bash build.sh makes an unsigned aligned APK unless KEYSTORE_PATH and KEYSTORE_PASSWORD_FILE point to your own private signing material. No signing secret is included.

## Privacy and branding
Nestcress runs offline without accounts, ads, analytics, third-party SDKs or requested permissions. Palette, optional room letters and solved-board marks stay in this app on your device. Clear app data or uninstall to remove them. The studio link opens your external browser.
GG007 original icon, menu studio https://ilanis-agent.github.io/gg-007-gaming/ and privacy.

## Preservation and publishing
Complete source/APK, exact cumulative 208-card studio and published catalog/studio sources and updater privately preserved at https://files.instinct.com/p6bh126akjh1-nestcress-source-archive . Repository https://github.com/iLanis-agent/nestcress holds README only; full Git source commit pending. Existing Jekyll static includes retained without changes; no Pages settings changes or client loader. Both site publications verified separately.
