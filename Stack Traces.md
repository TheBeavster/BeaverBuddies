# Desync - Error when new beaver is born - FIXED by other dev

## Trace
```
[Warning: Unity Log] [20-41-51.50] Unknown random called outside of tick
[Info   : Unity Log]   at BeaverBuddies.Plugin.LogStackTrace () [0x00000] in <867e2fe98ab8472eab2f4086239d1520>:0
  at BeaverBuddies.DeterminismService.LogUnknownRandomCalled () [0x00000] in <867e2fe98ab8472eab2f4086239d1520>:0
  at BeaverBuddies.DeterminismService.get_ShouldFreezeSeed () [0x00000] in <867e2fe98ab8472eab2f4086239d1520>:0
  at BeaverBuddies.DeterminismService.ShouldUseNonGameRNG () [0x00000] in <867e2fe98ab8472eab2f4086239d1520>:0
  at BeaverBuddies.RandomRangeIntPatcher.Prefix (System.Int32 inclusiveMin, System.Int32 exclusiveMax, System.Int32& __result) [0x00000] in <867e2fe98ab8472eab2f4086239d1520>:0
  at Timberborn.Common.RandomNumberGenerator.DMD<Timberborn.Common.RandomNumberGenerator::Range> (Timberborn.Common.RandomNumberGenerator , System.Int32 , System.Int32 ) [0x00000] in <ed85ad547402424491d24b7d34a5fea1>:0
  at Timberborn.Common.RandomNumberGenerator.GetListElement[T] (System.Collections.Generic.IReadOnlyList`1[T] list) [0x00000] in <ed85ad547402424491d24b7d34a5fea1>:0
  at Timberborn.Beavers.BeaverNameService.RandomName () [0x00000] in <93e526e1b383495aaae23dbda06965e8>:0
  at Timberborn.Beavers.BeaverEntityNamer.GenerateEntityName () [0x00000] in <93e526e1b383495aaae23dbda06965e8>:0
  at Timberborn.EntityNaming.NamedEntity.InitializeEntity () [0x00000] in <3a6b871511cc4bf3afabe25c65a54a66>:0
  at Timberborn.EntitySystem.EntityComponent.Initialize () [0x00000] in <ec6e914ba85f406bb6988b3d43ea3906>:0
  at Timberborn.EntitySystem.EntityComponent.InitializeIfUninitialized () [0x00000] in <ec6e914ba85f406bb6988b3d43ea3906>:0
  at Timberborn.EntitySystem.EntityComponent.Start () [0x00000] in <ec6e914ba85f406bb6988b3d43ea3906>:0
  at Timberborn.BaseComponentSystem.BaseComponentUnityAdapter.Start () [0x00000] in <57612b8fcdda4088b0e6a35ba9e6883f>:0
```
