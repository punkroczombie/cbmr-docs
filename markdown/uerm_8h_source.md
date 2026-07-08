<!-- source: http://scpcbmr.42web.io/uerm_8h_source.html -->
# SCP: Containment Breach 2 Scripting: uerm.h Source File

|  |  |  |
| --- | --- | --- |
| Logo | SCP: Containment Breach 2 Scripting |  |

![](sync_on.png "click to disable panel synchronization")

- [►](javascript:void(0))[SCP: Containment Breach 2 Scripting](index.md)

[•All](javascript:void(0))[Classes](javascript:void(0))[Functions](javascript:void(0))[Variables](javascript:void(0))[Modules](javascript:void(0))[Pages](javascript:void(0))

Loading...

Searching...

No Matches

uerm.h

1enum Callbacks

2{

3 ServerUpdate\_c = 1,

4 PlayerUpdate\_c = 2,

5 PlayerConnect\_c = 3,

6 PlayerChat\_c = 4,

7 PlayerDisconnect\_c = 5,

8 PlayerAttachesUpdate\_c = 6,

9 PlayerTakeItem\_c = 7,

10 PlayerDropItem\_c = 8,

11 PlayerDialogAction\_c = 9,

12 PlayerShootPlayer\_c = 10,

13 PlayerPressPlayer\_c = 11,

14 PlayerShoot\_c = 12,

15 PlayerConsole\_c = 13,

16 PlayerDeath\_c = 14,

17 PlayerRespawn\_c = 15,

18 WorldLoaded\_c = 16,

19 PlayerHitPlayer\_c = 17,

20 PlayerExploreCorpse\_c = 18,

21 PlayerClickObject\_c = 19,

22 PlayerShootObject\_c = 20,

23 PlayerUseDoorButton\_c = 21,

24 PlayerUseItem\_c = 22,

25 PlayerUse914\_c = 23,

26 FineItem\_c = 24,

27 WorldUpdate\_c = 25,

28 PlayerClickGui\_c = 26,

29 PlayerVoice\_c = 27,

30 PlayerTeleportElevator\_c = 28,

31 PlayerSelectItem\_c = 29,

32 ServerConsole\_c = 30,

33 ServerRestart\_c = 31,

34 PlayerShootNPC\_c = 32,

35 PlayerKeyAction\_c = 33,

36 OnLog\_c = 34,

37 IncomingConnection\_c = 35,

38 ShellDamagePlayer\_c = 36,

39 ShellExplode\_c = 37,

40 ConnectionLoaded\_c = 38,

41 ConnectionClosed\_c = 39,

42 CreateItem\_c = 39,

43 RemoveItem\_c = 40,

44 CreateNPC\_c = 41,

45 RemoveNPC\_c = 42,

46 CreateCorpse\_c = 43,

47 RemoveCorpse\_c = 44,

48 CreateObject\_c = 45,

49 RemoveObject\_c = 46,

50 CreateLight\_c = 47,

51 RemoveLight\_c = 48,

52 CreateGUIElement\_c = 49,

53 RemoveGUIElement\_c = 50,

54 CreateShell\_c = 51,

55 RemoveShell\_c = 52,

56 PlayerSpectateAction\_c = 53

57};

58

59const string[] EventCallbacks =

60{

61 "",

62 "OnServerUpdate",

63 "OnPlayerUpdate",

64 "OnPlayerConnect",

65 "OnPlayerChat",

66 "OnPlayerDisconnect",

67 "OnPlayerAttachesUpdate",

68 "OnPlayerTakeItem",

69 "OnPlayerDropItem",

70 "OnPlayerDialogAction",

71 "OnPlayerShootPlayer",

72 "OnPlayerPressPlayer",

73 "OnPlayerShoot",

74 "OnPlayerConsole",

75 "OnPlayerDeath",

76 "OnPlayerRespawn",

77 "OnWorldLoaded",

78 "OnPlayerHitPlayer",

79 "OnPlayerExploreCorpse",

80 "OnPlayerClickObject",

81 "OnPlayerShootObject",

82 "OnPlayerUseDoorButton",

83 "OnPlayerUseItem",

84 "OnPlayerUse914",

85 "OnFineItem",

86 "OnWorldUpdate",

87 "OnPlayerClickGUIElement",

88 "OnPlayerVoice",

89 "OnPlayerTeleportElevator",

90 "OnPlayerSelectItem",

91 "OnServerConsole",

92 "OnServerRestart",

93 "OnPlayerShootNPC",

94 "OnPlayerKeyAction",

95 "OnLogMessage",

96 "OnIncomingConnection",

97 "OnShellDamagePlayer",

98 "OnShellExplode",

99 "OnConnectionLoaded",

100 "OnConnectionClosed",

101 "OnCreateItem",

102 "OnRemoveItem",

103 "OnCreateNPC",

104 "OnRemoveNPC",

105 "OnCreateCorpse",

106 "OnRemoveCorpse",

107 "OnCreateObject",

108 "OnRemoveObject",

109 "OnCreateLight",

110 "OnRemoveLight",

111 "OnCreateGUIElement",

112 "OnRemoveGUIElement",

113 "OnCreateShell",

114 "OnRemoveShell",

115 "OnPlayerSpectateAction"

116};

117

118enum Dialog

119{

120 DIALOG\_TYPE\_MESSAGE = 0,

121 DIALOG\_TYPE\_LIST = 1,

122 DIALOG\_TYPE\_INPUT = 2

123};

124

125enum DefaultModels

126{

127 CLASS\_D\_MODEL = 1,

128 HAZMAT\_MODEL = 2,

129 SCP\_173\_MODEL = 3,

130 SCP\_106\_MODEL = 4,

131 SCP\_049\_MODEL = 5,

132 SCP\_939\_MODEL = 6,

133 SCP\_966\_MODEL = 7,

134 SCP\_096\_MODEL = 8,

135 GUARD\_MODEL = 9,

136 MTF\_MODEL = 10,

137 CHAOS\_MODEL = 11,

138 ZOMBIE\_MODEL = 12,

139 ZOMBIE\_GUARD\_MODEL = 13,

140 SCP\_999\_MODEL = 14,

141 SCP\_860\_MODEL = 15,

142 GOC\_MODEL = 16,

143 SCP\_457\_MODEL = 17

144};

145

146enum DefaultModelTextures

147{

148 CLASS\_D\_1\_TEXTURE = 1,

149 CLASS\_D\_2\_TEXTURE = 2,

150 CLASS\_D\_3\_TEXTURE = 3,

151 CLASS\_D\_4\_TEXTURE = 4,

152 CLASS\_D\_5\_TEXTURE = 5,

153 CLASS\_D\_6\_TEXTURE = 6,

154 HAZMAT\_TEXTURE = 7,

155 CORPSE\_CLASS\_D\_TEXTURE = 8,

156 HAZMAT\_HEAVY\_TEXTURE = 9,

157 SCIENTIST\_1\_TEXTURE = 10,

158 SCIENTIST\_2\_TEXTURE = 11,

159 SCIENTIST\_3\_TEXTURE = 12,

160 SCIENTIST\_4\_TEXTURE = 13,

161 SCIENTIST\_5\_TEXTURE = 14,

162 SCIENTIST\_6\_TEXTURE = 15,

163 SCIENTIST\_7\_TEXTURE = 16,

164 JANITOR\_TEXTURE = 17,

165 CHAOS\_TEXTURE = 18,

166 MTF\_TEXTURE = 19,

167 GUARD\_TEXTURE = 20,

168 CLASS\_D\_ZOMBIE\_TEXTURE = 21,

169 SCIENTIST\_ZOMBIE\_TEXTURE = 22,

170 JANITOR\_ZOMBIE\_TEXTURE = 23,

171 HAZMAT\_ZOMBIE\_TEXTURE = 24,

172 MTF\_COMMANDER\_TEXTURE = 25,

173 MTF\_MEDIC\_TEXTURE = 26,

174 MTF\_SERGEANT\_TEXTURE = 27,

175 SCP\_096\_BLOODY\_TEXTURE = 28,

176 CHAOS\_COMMANDER\_TEXTURE = 29,

177 GOC\_TEXTURE = 30,

178 SCP\_939\_EMISSIVE\_TEXTURE = 31,

179 CHAOS\_EMISSIVE\_TEXTURE = 32

180};

181

182enum PlayerAnimations

183{

184 PLAYER\_MODEL\_ANIMATION\_IDLE = 1,

185 PLAYER\_MODEL\_ANIMATION\_WALK = 2,

186 PLAYER\_MODEL\_ANIMATION\_RUN = 3,

187 PLAYER\_MODEL\_ANIMATION\_SITTING\_IDLE = 4,

188 PLAYER\_MODEL\_ANIMATION\_SITTING\_WALK = 5,

189 PLAYER\_MODEL\_ANIMATION\_FALLING = 6,

190 PLAYER\_MODEL\_ANIMATION\_FELL = 7,

191 PLAYER\_MODEL\_ANIMATION\_INJURED\_IDLE = 8,

192 PLAYER\_MODEL\_ANIMATION\_INJURED\_WALK = 9,

193 PLAYER\_MODEL\_ANIMATION\_IDLE\_ARMED\_PISTOL = 10,

194 PLAYER\_MODEL\_ANIMATION\_WALK\_ARMED\_PISTOL = 11,

195 PLAYER\_MODEL\_ANIMATION\_RUN\_ARMED\_PISTOL = 12,

196 PLAYER\_MODEL\_ANIMATION\_SITTING\_IDLE\_ARMED\_PISTOL = 13,

197 PLAYER\_MODEL\_ANIMATION\_SITTING\_WALK\_ARMED\_PISTOL = 14,

198 PLAYER\_MODEL\_ANIMATION\_IDLE\_ARMED\_RIFLE = 15,

199 PLAYER\_MODEL\_ANIMATION\_WALK\_ARMED\_RIFLE = 16,

200 PLAYER\_MODEL\_ANIMATION\_RUN\_ARMED\_RIFLE = 17,

201 PLAYER\_MODEL\_ANIMATION\_SITTING\_IDLE\_ARMED\_RIFLE = 18,

202 PLAYER\_MODEL\_ANIMATION\_SITTING\_WALK\_ARMED\_RIFLE = 19,

203 PLAYER\_MODEL\_ANIMATION\_ZOMBIE\_HIT = 20

204};

205enum DefaultAttaches

206{

207 GASMASK\_ATTACHMODEL = 1,

208 GASMASK\_FINE\_ATTACHMODEL = 2,

209 GASMASK\_VERYFINE\_ATTACHMODEL = 3,

210 GASMASK\_HEAVY\_ATTACHMODEL = 4,

211

212 VEST\_ATTACHMODEL = 5,

213 VEST\_FINE\_ATTACHMODEL = 6,

214

215 HELMET\_ATTACHMODEL = 7,

216

217 NVG\_ATTACHMODEL = 8,

218 NVG\_FINE\_ATTACHMODEL = 9,

219 NVG\_VERYFINE\_ATTACHMODEL = 10,

220

221 SCRAMBLE\_ATTACHMODEL = 11,

222 SCRAMBLE\_FINE\_ATTACHMODEL = 12,

223

224 SCP427\_ATTACHMODEL = 13,

225

226 CAP\_ATTACHMODEL = 14,

227 SCP268\_ATTACHMODEL = 15,

228 SCP268\_FINE\_ATTACHMODEL = 16,

229

230 SCP714\_ATTACHMODEL = 17,

231 SCP714\_COARSE\_ATTACHMODEL = 18,

232

233 WEAPON\_M4A1\_ATTACHMODEL = 19,

234 WEAPON\_GLOCK\_ATTACHMODEL = 20,

235 WEAPON\_M60\_ATTACHMODEL = 21,

236 WEAPON\_SR\_ATTACHMODEL = 22,

237 WEAPON\_MP5\_ATTACHMODEL = 23,

238 WEAPON\_FS\_ATTACHMODEL = 24,

239 WEAPON\_VECTOR\_ATTACHMODEL = 25,

240 WEAPON\_CUFFS\_ATTACHMODEL = 26,

241 WEAPON\_CUFFED\_ATTACHMODEL = 27,

242 SCP035\_ATTACHMODEL = 28,

243 FINE\_HELMET\_ATTACHMODEL = 29,

244 WEAPON\_P90\_ATTACHMODEL = 30,

245 WEAPON\_MP7\_ATTACHMODEL = 31,

246 WEAPON\_M134\_ATTACHMODEL = 32,

247 WEAPON\_VIEWMODEL096\_ATTACHMODEL = 33,

248 WEAPON\_VIEWMODEL049\_ATTACHMODEL = 34,

249 WEAPON\_VIEWMODEL106\_ATTACHMODEL = 35,

250 WEAPON\_VIEWMODEL173\_ATTACHMODEL = 36,

251 WEAPON\_VIEWMODEL966\_ATTACHMODEL = 37,

252 WEAPON\_REMINGTON\_ATTACHMODEL = 38,

253 WEAPON\_RPG\_ATTACHMODEL = 39,

254 WEAPON\_G36\_ATTACHMODEL = 40,

255 WEAPON\_AK74\_ATTACHMODEL = 41,

256

257 WEAPON\_COIN\_ATTACHMODEL = 499,

258 WEAPON\_KEY860\_ATTACHMODEL = 500,

259 WEAPON\_KEY\_ATTACHMODEL = 501,

260 WEAPON\_EMP\_ATTACHMODEL = 502,

261 WEAPON\_STEMTEX\_ATTACHMODEL = 503,

262 WEAPON\_KNIFE\_ATTACHMODEL = 504,

263 WEAPON\_M69\_ATTACHMODEL = 505,

264 WEAPON\_SCP005\_ATTACHMODEL = 506,

265 WEAPON\_SEVEREDHAND\_ATTACHMODEL = 507,

266 WEAPON\_HACKINGDEVICE\_ATTACHMODEL = 508,

267 WEAPON\_SNAV\_ATTACHMODEL = 509,

268 WEAPON\_RADIO\_ATTACHMODEL = 510,

269 WEAPON\_KEYCARD\_ATTACHMODEL = 511

270};

271

272enum AttachesParts // Default reserved attach parts for SetAttach

273{

274 ATTACH\_FACE = 0,

275 ATTACH\_BODY = 1,

276 ATTACH\_HEAD = 2,

277 ATTACH\_NECK = 3,

278 ATTACH\_FINGER = 4,

279 ATTACH\_WEAPON = 5,

280 ATTACH\_WRIST = 6,

281 ATTACH\_CUSTOM1 = 7,

282 ATTACH\_CUSTOM2 = 8,

283 ATTACH\_CUSTOM3 = 9

284};

285

286enum DefaultWeapons

287{

288 WEAPON\_M4A1 = 1,

289 WEAPON\_GLOCK = 2,

290 WEAPON\_M60 = 3,

291 WEAPON\_SR = 4,

292 WEAPON\_MP5 = 5,

293 WEAPON\_FS = 6,

294 WEAPON\_VECTOR = 7,

295 WEAPON\_CUFFS = 8,

296 WEAPON\_CUFFED = 9,

297 WEAPON\_P90 = 10,

298 WEAPON\_MP7 = 11,

299 WEAPON\_M134 = 12,

300 WEAPON\_VIEWMODEL096 = 13,

301 WEAPON\_VIEWMODEL049 = 14,

302 WEAPON\_VIEWMODEL106 = 15,

303 WEAPON\_VIEWMODEL173 = 16,

304 WEAPON\_VIEWMODEL966 = 17,

305 WEAPON\_REMINGTON = 18,

306 WEAPON\_RPG = 19,

307 WEAPON\_G36 = 20,

308 WEAPON\_AK74 = 21,

309

310 // It's better to add new weapons via addons until 128 id

311 WEAPON\_COIN = 243,

312 WEAPON\_KEY860 = 244,

313 WEAPON\_KEY = 245,

314 WEAPON\_EMP = 246,

315 WEAPON\_STEMTEX = 247,

316 WEAPON\_KNIFE = 248,

317 WEAPON\_M69 = 249,

318 WEAPON\_SCP005 = 250,

319 WEAPON\_SEVEREDHAND = 251,

320 WEAPON\_HACKINGDEVICE = 252,

321 WEAPON\_SNAV = 253,

322 WEAPON\_RADIO = 254,

323 WEAPON\_KEYCARD = 255

324};

325

326enum RoomIdentifiers

327{

328 // ~ LCZ

329 r\_room1\_storage = 0,

330 r\_room1\_dead\_end\_lcz = 1,

331 r\_cont1\_005 = 2,

332 r\_cont1\_173 = 3, r\_cont1\_173\_intro = 4, r\_cont1\_205 = 5, r\_cont1\_914 = 6,

333 r\_room2\_lcz = 7, r\_room2\_2\_lcz = 8, r\_room2\_3\_lcz = 9, r\_room2\_4\_lcz = 10, r\_room2\_5\_lcz = 11, r\_room2\_6\_lcz = 12, r\_room2\_7\_lcz = 13,

334 r\_room2\_closets = 14,

335 r\_room2\_elevator = 15,

336 r\_room2\_gw = 16, r\_room2\_gw\_2 = 17,

337 r\_room2\_js = 18,

338 r\_room2\_sl = 19,

339 r\_room2\_storage = 20,

340 r\_room2\_tesla\_lcz = 21,

341 r\_room2\_test\_lcz = 22,

342 r\_cont2\_012 = 23, r\_cont2\_427\_714\_860\_1025 = 24, r\_cont2\_500\_1499 = 25, r\_cont2\_1123 = 26,

343 r\_room2c\_lcz = 27, r\_room2c\_2\_lcz = 28,

344 r\_room2c\_gw\_lcz = 29, r\_room2c\_gw\_2\_lcz = 30,

345 r\_cont2c\_066\_1162\_arc = 31,

346 r\_room3\_storage = 32,

347 r\_room3\_lcz = 33, r\_room3\_2\_lcz = 34, r\_room3\_3\_lcz = 35,

348 r\_cont3\_372 = 36,

349 r\_room4\_lcz = 37, r\_room4\_2\_lcz = 38,

350 r\_room4\_ic = 39,

351 // ~ CHECKPOINT

352 r\_room2\_checkpoint\_lcz\_hcz = 40,

353 // ~ HCZ

354 r\_room1\_dead\_end\_hcz = 41,

355 r\_cont1\_035 = 42, r\_cont1\_079 = 43, r\_cont1\_106 = 44, r\_cont1\_895 = 45,

356 r\_room2\_hcz = 46, r\_room2\_2\_hcz = 47, r\_room2\_3\_hcz = 48, r\_room2\_4\_hcz = 49, r\_room2\_5\_hcz = 50, r\_room2\_6\_hcz = 51, r\_room2\_7\_hcz = 52,

357 r\_room2\_mt = 53, r\_cont2\_457 = 53,

358 r\_room2\_nuke = 54,

359 r\_room2\_servers\_hcz = 55,

360 r\_room2\_shaft = 56,

361 r\_room2\_tesla\_hcz = 57,

362 r\_room2\_test\_hcz = 58,

363 r\_cont2\_008 = 59, r\_cont2\_049 = 60, r\_cont2\_409 = 61,

364 r\_room2c\_hcz = 62, r\_room2c\_2\_hcz = 63, r\_room2c\_3\_hcz = 64,

365 r\_cont2c\_096 = 65,

366 r\_room3\_hcz = 66, r\_room3\_2\_hcz = 67, r\_room3\_3\_hcz = 68,

367 r\_cont3\_513 = 69, r\_cont3\_966 = 70,

368 r\_room4\_hcz = 71, r\_room4\_2\_hcz = 72, r\_room4\_3\_hcz = 73,

369 // ~ CHECKPOINT

370 r\_room2\_checkpoint\_hcz\_ez = 74,

371 // ~ EZ

372 r\_gate\_a\_entrance = 75, r\_gate\_a = 76, r\_gate\_b\_entrance = 77, r\_gate\_b = 78,

373 r\_room1\_dead\_end\_ez = 79,

374 r\_room1\_lifts = 80,

375 r\_room1\_cmr = 81,

376 r\_room2\_ez = 82, r\_room2\_2\_ez = 83, r\_room2\_3\_ez = 84, r\_room2\_4\_ez = 85, r\_room2\_5\_ez = 86, r\_room2\_6\_ez = 87, r\_room2\_7\_ez = 88,

377 r\_room2\_cafeteria = 89,

378 r\_room2\_ic = 90,

379 r\_room2\_medibay = 91,

380 r\_room2\_office = 92, r\_room2\_office\_2 = 93, r\_room2\_office\_3 = 94,

381 r\_room2\_servers\_ez = 95,

382 r\_room2\_scientists = 96, r\_room2\_scientists\_2 = 97,

383 r\_room2\_tesla\_ez = 98,

384 r\_cont2\_860\_1 = 99,

385 r\_room2c\_ez = 100, r\_room2c\_2\_ez = 101,

386 r\_room2c\_ec = 102,

387 r\_room3\_gw = 103,

388 r\_room3\_office = 104,

389 r\_room3\_ez = 105, r\_room3\_2\_ez = 106, r\_room3\_3\_ez = 107, r\_room3\_4\_ez = 108,

390 r\_room4\_ez = 109, r\_room4\_2\_ez = 110,

391 // ~ OTHERS

392 r\_dimension\_106 = 111, r\_dimension\_1499 = 112,

393 r\_room2\_closets\_2 = 113,

394 r\_gate\_a\_b = 114,

395 r\_cont3\_009 = 115,

396 r\_room2\_tesla\_2\_hcz = 116,

397 r\_room4\_gw = 117,

398 r\_room4\_3\_lcz = 118,

399 r\_room4\_3\_ez = 119,

400 r\_room2c\_research = 120,

401 r\_RESERVED = 300 // Rooms ID to 300 are reserved for future versions of CB2

402};

403

404enum EventIdentifiers

405{

406 // ~ LCZ

407 e\_room1\_dead\_end\_106 = 0,

408 e\_room1\_storage = 1,

409 e\_cont1\_005 = 2,

410 e\_cont1\_173 = 3, e\_cont1\_173\_intro = 4,

411 e\_cont1\_205 = 5,

412 e\_cont1\_914 = 6,

413 e\_room2\_2\_lcz\_fan = 7,

414 e\_room2\_closets = 8,

415 e\_room2\_elevator = 9,

416 e\_room2\_gw\_2 = 10,

417 e\_room2\_storage = 11,

418 e\_room2\_sl = 12,

419 e\_room2\_test\_lcz\_173 = 13,

420 e\_cont2\_012 = 14,

421 e\_cont2\_500\_1499 = 15,

422 e\_cont2\_1123 = 16,

423 e\_cont2c\_066\_1162\_arc = 17,

424 e\_room3\_storage = 18,

425 e\_cont3\_372 = 19,

426 e\_room4\_ic = 20,

427 // ~ HCZ

428 e\_cont1\_035 = 21,

429 e\_cont1\_079 = 22,

430 e\_cont1\_106 = 23,

431 e\_cont1\_895 = 24,

432 e\_room2\_2\_hcz\_106 = 25,

433 e\_room2\_4\_hcz\_106 = 26,

434 e\_room2\_5\_hcz\_106 = 27,

435 e\_room2\_6\_hcz\_smoke = 28, e\_room2\_6\_hcz\_173 = 29,

436 e\_room2\_mt = 30,

437 e\_room2\_nuke = 31,

438 e\_room2\_servers\_hcz = 32,

439 e\_room2\_shaft = 33,

440 e\_room2\_test\_hcz = 34,

441 e\_cont2\_008 = 35,

442 e\_cont2\_049 = 36,

443 e\_cont2\_409 = 37,

444 e\_room3\_hcz\_duck = 38, e\_room3\_hcz\_1048 = 39,

445 e\_room3\_2\_hcz\_guard = 40,

446 e\_room2\_office\_3 = 41,

447 e\_cont3\_966 = 42,

448 e\_room4\_2\_hcz\_d = 43,

449 // ~ EZ

450 e\_gate\_b\_entrance = 44, e\_gate\_b = 45,

451 e\_gate\_a\_entrance = 46, e\_gate\_a = 47,

452 e\_room1\_dead\_end\_guard = 48,

453 e\_room2\_ez\_035 = 49,

454 e\_room2\_2\_ez\_duck = 50,

455 e\_room2\_6\_ez\_789\_j = 51, e\_room2\_6\_ez\_guard = 52,

456 e\_room2\_office = 53,

457 e\_room2\_cafeteria = 54,

458 e\_room2\_ic = 55,

459 e\_room2\_medibay = 56,

460 e\_room2\_scientists\_2 = 57,

461 e\_cont2\_860\_1 = 58,

462 e\_room2c\_ec = 59,

463 e\_room3\_2\_ez\_duck = 60,

464 // ~ OTHERS

465 e\_096\_spawn = 61,

466 e\_106\_victim = 62,

467 e\_106\_victim\_wall = 63,

468 e\_106\_sinkhole = 64,

469 e\_173\_appearing = 65,

470 e\_682\_roar = 66,

471 e\_1048\_a = 67,

472 e\_blackout = 68,

473 e\_checkpoint = 69,

474 e\_door\_closing = 70,

475 e\_gateway = 71,

476 e\_tesla = 72,

477 e\_trick = 73, e\_trick\_item = 74,

478 e\_dimension\_106 = 75, e\_dimension\_1499 = 76,

479 // ~ NEW VERSIONS

480 e\_gate\_a\_b = 77,

481 e\_cont3\_009 = 78,

482 e\_broken\_tesla = 79,

483 e\_room2c\_gw\_lcz = 80

484};

485

486enum ItemsIdentifiers

487{

488 it\_paper = 0,

489 it\_oldpaper = 1,

490

491 it\_origami = 2,

492

493 it\_badge = 3,

494 it\_badge2 = 4,

495

496 it\_ticket = 5,

497 //[SCPs AND VARIATIONS]

498 it\_scp005 = 6,

499 it\_coarse005 = 7,

500 it\_crystal005 = 8,

501

502 it\_scp148ingot = 9,

503 it\_scp148 = 10,

504

505 it\_cap = 11,

506 it\_scp268 = 12,

507 it\_fine268 = 13,

508

509 it\_scp420j = 14,

510 it\_cigarette = 15,

511 it\_joint = 16,

512 it\_joint\_smelly = 17,

513

514 it\_scp427 = 18,

515 it\_scp500 = 19,

516 it\_scp500pill = 20,

517 it\_scp500pilldeath = 21,

518 it\_pill = 22,

519

520 it\_scp513 = 23,

521

522 it\_coarse714 = 24,

523 it\_scp714 = 25,

524 it\_fine714 = 26,

525 it\_ring = 27,

526

527 it\_scp860 = 28,

528 it\_fine860 = 29,

529

530 it\_scp1025 = 30,

531 it\_fine1025 = 31,

532 it\_book = 32,

533

534 it\_scp1123 = 33,

535

536 it\_scp1499 = 34,

537 it\_fine1499 = 35,

538

539 it\_scp2022 = 36,

540 it\_scp2022pill = 37,

541

542 // [MISC ITEMS]

543 it\_helmet = 38,

544

545 it\_vest = 39,

546 it\_finevest = 40,

547 it\_corrvest = 41,

548 it\_veryfinevest = 42,

549

550 it\_cup = 43,

551 it\_emptycup = 44,

552

553 it\_clipboard = 45,

554 it\_wallet = 46,

555

556 it\_electronics = 47,

557

558 it\_eyedrops = 48,

559 it\_eyedrops2 = 49,

560 it\_fineeyedrops = 50,

561 it\_veryfineeyedrops = 51,

562

563 it\_firstaid = 52,

564 it\_firstaid2 = 53,

565 it\_finefirstaid = 54,

566 it\_veryfinefirstaid = 55,

567

568 it\_gasmask = 56,

569 it\_finegasmask = 57,

570 it\_veryfinegasmask = 58,

571 it\_gasmask148 = 59,

572

573 it\_hazmatsuit = 60,

574 it\_finehazmatsuit = 61,

575 it\_veryfinehazmatsuit = 62,

576 it\_hazmatsuit148 = 63,

577

578 it\_nvg = 64,

579 it\_veryfinenvg = 65,

580 it\_finenvg = 66,

581 it\_scramble = 67,

582 it\_finescramble = 68,

583

584 it\_radio = 69,

585 it\_18vradio = 70,

586 it\_fineradio = 71,

587 it\_veryfineradio = 72,

588

589 it\_nav = 73,

590 it\_nav300 = 74,

591 it\_nav310 = 75,

592 it\_navulti = 76,

593

594 it\_e\_reader = 77,

595 it\_e\_reader20 = 78,

596 it\_e\_readerulti = 79,

597

598 it\_bat = 80,

599 it\_coarsebat = 81,

600 it\_finebat = 82,

601 it\_veryfinebat = 83,

602 it\_killbat = 84,

603

604 it\_syringe = 85,

605 it\_finesyringe = 86,

606 it\_veryfinesyringe = 87,

607 it\_syringeinf = 88,

608

609 // [KEYCARDS, HANDS, KEYS, CARDS, COINS]

610 it\_key0 = 89,

611 it\_key1 = 90,

612 it\_key2 = 91,

613 it\_key3 = 92,

614 it\_key4 = 93,

615 it\_key5 = 94,

616 it\_key6 = 95,

617 it\_keyomni = 96,

618

619 it\_mastercard = 97,

620 it\_mastercard\_golden = 98,

621 it\_playcard = 99,

622

623 it\_hand = 100,

624 it\_hand2 = 101,

625 it\_hand3 = 102,

626

627 it\_key\_yellow = 103,

628 it\_key\_white = 104,

629 it\_lostkey = 105,

630

631 it\_25ct = 106,

632 it\_coin = 107,

633

634 it\_pizza = 108,

635

636 //

637 it\_m4 = 109,

638 it\_glock = 110,

639 it\_m60 = 111,

640 it\_sr556 = 112,

641 it\_mp5 = 113,

642 it\_fs = 114,

643 it\_krissvector = 115,

644

645 it\_finehelmet = 116,

646 it\_keyci = 117,

647 it\_p90 = 118,

648 it\_mp7 = 119,

649 it\_handcuffs = 120,

650 it\_m134 = 121,

651 it\_remington = 122,

652

653 it\_fine513 = 123,

654

655 it\_backpack = 124,

656 it\_ammocrate = 125,

657 it\_headphones = 126,

658 it\_rpg = 127,

659 it\_g36 = 128,

660 it\_ak74 = 129,

661 it\_m69 = 130,

662 it\_m9 = 131,

663 it\_stemtex = 132,

664 it\_emp = 133,

665 it\_RESERVETO = 500 // Items ID to 500 are reserved for future versions of CB2

666};

667

668enum DoorTypes

669{

670 DEFAULT\_DOOR = 0,

671 ELEVATOR\_DOOR = 1,

672 HEAVY\_DOOR = 2,

673 BIG\_DOOR = 3,

674 OFFICE\_DOOR = 4,

675 WOODEN\_DOOR = 5,

676 FENCE\_DOOR = 6,

677 ONE\_SIDED\_DOOR = 7,

678 SCP\_914\_DOOR = 8

679};

680

681enum DoorAccess

682{

683 NONE,

684 DOOR\_KEYCARD,

685 DOOR\_DNA,

686 DOOR\_KEYPAD,

687 DOOR\_OWF,

688 DOOR\_ELEVATOR

689};

690

691enum DoorKeycards

692{

693 KEY\_MISC = 0,

694 KEY\_CARD\_6 = 1,

695 KEY\_CARD\_0 = 2,

696 KEY\_CARD\_1 = 3,

697 KEY\_CARD\_2 = 4,

698 KEY\_CARD\_3 = 5,

699 KEY\_CARD\_4 = 6,

700 KEY\_CARD\_5 = 7,

701 KEY\_CARD\_OMNI = 8,

702 KEY\_005 = 9,

703 KEY\_HAND\_WHITE = -1,

704 KEY\_HAND\_BLACK = -2,

705 KEY\_HAND\_YELLOW = -3,

706 KEY\_860 = -4,

707 KEY\_KEY = -5,

708 KEY\_KEY2 = -6,

709 KEY\_LOST\_KEY = -66

710};

711

712enum SCP914

713{

714 ROUGH = -2,

715 COARSE = -1,

716 ONETOONE = 0,

717 FINE = 1,

718 VERYFINE = 2

719};

720

721enum KickCodes

722{

723 CODE\_UNALLOWEDVERSION = 1,

724 CODE\_TOOMUCHPLAYERS = 2,

725 CODE\_WRONGSEED = 3,

726 CODE\_NOTRESPOND = 4,

727 CODE\_LOBBYFAILED = 5,

728 CODE\_STEAMAUTH = 6,

729 CODE\_INVALIDPASSWORD = 7,

730 CODE\_BANNED = 8,

731 CODE\_KICKED = 9,

732 CODE\_RESTART = 10,

733 CODE\_INVALIDCONTENT = 11,

734 CODE\_CUSTOMERROR = 12

735};

736

737enum NPCTypes

738{

739 NPCType008\_1 = 0, NPCType008\_1\_Surgeon = 1, NPCType035\_Tentacle = 2, NPCType049 = 3, NPCType049\_2 = 4, NPCType066 = 5, NPCType096 = 6,

740 NPCType106 = 7, NPCType173 = 8, NPCType372 = 9, NPCType513\_1 = 10, NPCType860\_2 = 11, NPCType939 = 12,

741 NPCType966 = 13, NPCType999 = 14, NPCType1048 = 15, NPCType1048\_A = 16, NPCType1499\_1 = 17,

742 NPCTypeApache = 18, NPCTypeClerk = 19, NPCTypeD = 20, NPCTypeGuard = 21, NPCTypeMTF = 22, NPCTypeCockroach = 23

743};

744

745enum Fonts

746{

747 Font\_Default = 0,

748 Font\_Default\_Big = 1,

749 Font\_Digital = 2,

750 Font\_Digital\_Big = 3,

751 Font\_Journal = 4,

752 Font\_Console = 5,

753 Font\_Credits = 6,

754 Font\_Credits\_Big = 7,

755 Font\_Tahoma = 8,

756 Font\_Icons = 9,

757 Font\_Default\_Medium = 10,

758 Font\_Icons\_Big = 11,

759 Font\_Console\_Small = 12,

760 Font\_Default\_Small = 13

761};

762

763enum KeysTypes

764{

765 KEY\_U = 0x01,

766 KEY\_I = 0x02,

767 KEY\_O = 0x04,

768 KEY\_P = 0x08,

769 KEY\_N = 0x10,

770 KEY\_M = 0x20,

771 KEY\_F2 = 0x40,

772 KEY\_F4 = 0x80,

773 KEY\_LMB = 0x100,

774 KEY\_RMB = 0x200,

775 KEY\_ALT = 0x400,

776 KEY\_F = 0x800,

777 KEY\_G = 0x1000,

778 KEY\_H = 0x2000,

779 KEY\_J = 0x4000,

780 KEY\_K = 0x8000,

781 KEY\_1 = 0x10000,

782 KEY\_2 = 0x20000,

783 KEY\_3 = 0x40000,

784 KEY\_4 = 0x80000,

785 KEY\_5 = 0x100000,

786 KEY\_6 = 0x200000,

787 KEY\_7 = 0x400000,

788 KEY\_8 = 0x800000,

789 KEY\_9 = 0x1000000,

790 KEY\_0 = 0x2000000,

791 KEY\_F9 = 0x4000000,

792 KEY\_F10 = 0x8000000,

793 KEY\_Z = 0x10000000,

794 KEY\_X = 0x20000000,

795 KEY\_JUMP = 0x40000000,

796 KEY\_SPRINT = int(0x80000000)

797};

798

799enum MouseTypes

800{

801 MOUSE\_LMB = 0x01,

802 MOUSE\_RMB = 0x02,

803 MOUSE\_MMB = 0x04

804};

805

806const float ROOM\_SCALE = 8.0 / 2048.0;

807

808// Players range is 1..240

809const int MAX\_PLAYERS = 240;

810

811const int MAX\_DOORS = 1000;

812const int MAX\_ROOMS = 256;

813const int MAX\_EVENTS = 256;

814const int MAX\_NPCS = 256;

815const int MAX\_CORPSE\_INVENTORY = 10;

816const int MAX\_PLAYER\_INVENTORY = 10;

817const int MAX\_PLAYER\_TAGS = 6;

818

819// Indexes starting from 0 without -1

820const int MAX\_ROOM\_DOORS = 8; // 0..8

821

822// WMIDs for GetHWID

823const int WMI\_ALL = 0;

824const int WMI\_UUID = 1;

825const int WMI\_SERIALNUMBER = 2;

826const int WMI\_HDD = 3;

827const int WMI\_IDENTNUM = 4;

828const int WMI\_BASESERIALNUMBER = 5;

829const int WMI\_MACADDRESS = 6;

- **uerm.h**
- Generated by [![doxygen](doxygen.svg)](https://www.doxygen.org/index.html) 1.13.2
