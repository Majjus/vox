---- Minecraft Crash Report ----
// I'm sorry, Dave.

Time: 27/01/15 09:28
Description: Rendering screen

java.lang.OutOfMemoryError: Java heap space
	at com.thevoxelbox.voxelmap.b.w.<init>(Unknown Source)
	at com.thevoxelbox.voxelmap.b.c.<init>(Unknown Source)
	at com.thevoxelbox.voxelmap.b.j.a(Unknown Source)
	at com.thevoxelbox.voxelmap.b.g.a(Unknown Source)
	at cji.b(SourceFile:1020)
	at bsu.as(SourceFile:903)
	at bsu.a(SourceFile:314)
	at net.minecraft.client.main.Main.main(SourceFile:120)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:483)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)


A detailed walkthrough of the error, its code path and all known details is as follows:
---------------------------------------------------------------------------------------

-- Head --
Stacktrace:
	at com.thevoxelbox.voxelmap.b.w.<init>(Unknown Source)
	at com.thevoxelbox.voxelmap.b.c.<init>(Unknown Source)
	at com.thevoxelbox.voxelmap.b.j.a(Unknown Source)
	at com.thevoxelbox.voxelmap.b.g.a(Unknown Source)

-- Screen render details --
Details:
	Screen name: com.thevoxelbox.voxelmap.b.g
	Mouse location: Scaled: (649, 424). Absolute: (1298, 201)
	Screen size: Scaled: (840, 525). Absolute: (1680, 1050). Scale factor of 2

-- Affected level --
Details:
	Level name: MpServer
	All players: 1 total; [cio['majjus_'/8745181, l='MpServer', x=-36347.64, y=97.00, z=-425.91]]
	Chunk stats: MultiplayerChunkCache: 441, 441
	Level seed: 0
	Level generator: ID 00 - default, ver 1. Features enabled: false
	Level generator options: 
	Level spawn location: 0.00,64.00,0.00 - World: (0,64,0), Chunk: (at 0,4,0 in 0,0; contains blocks 0,0,0 to 15,255,15), Region: (0,0; contains chunks 0,0 to 31,31, blocks 0,0,0 to 511,255,511)
	Level time: 811485468 game time, 811775410 day time
	Level dimension: 0
	Level storage version: 0x00000 - Unknown?
	Level weather: Rain time: 0 (now: false), thunder time: 0 (now: false)
	Level game mode: Game mode: survival (ID 0). Hardcore: false. Cheats: false
	Forced entities: 24 total; [cio['majjus_'/8745181, l='MpServer', x=-36347.64, y=97.00, z=-425.91], aep['Creeper'/8745189, l='MpServer', x=-36335.50, y=63.00, z=-459.50], age['Spider'/8745188, l='MpServer', x=-36337.50, y=63.00, z=-463.50], aep['Creeper'/8745191, l='MpServer', x=-36332.50, y=31.00, z=-389.50], abs['Cow'/8745190, l='MpServer', x=-36320.75, y=64.00, z=-404.34], abs['Cow'/8745185, l='MpServer', x=-36370.50, y=79.00, z=-427.56], adw['item.item.rottenFlesh'/8745184, l='MpServer', x=-36350.22, y=63.02, z=-434.56], abs['Cow'/8745187, l='MpServer', x=-36369.16, y=83.00, z=-424.50], agi['Witch'/8746415, l='MpServer', x=-36377.50, y=34.00, z=-411.50], afw['Skeleton'/8745710, l='MpServer', x=-36358.50, y=63.00, z=-471.50], agi['Witch'/8746414, l='MpServer', x=-36372.50, y=34.00, z=-410.50], afw['Skeleton'/8745193, l='MpServer', x=-36331.50, y=32.00, z=-390.50], age['Spider'/8745705, l='MpServer', x=-36359.50, y=63.00, z=-465.50], afw['Skeleton'/8745192, l='MpServer', x=-36330.50, y=29.00, z=-387.50], afw['Skeleton'/8746472, l='MpServer', x=-36307.50, y=34.00, z=-450.50], aep['Creeper'/8745194, l='MpServer', x=-36313.50, y=63.00, z=-456.50], age['Spider'/8745706, l='MpServer', x=-36361.50, y=63.00, z=-468.50], agj['Zombie'/8745205, l='MpServer', x=-36303.50, y=51.00, z=-404.50], aep['Creeper'/8746483, l='MpServer', x=-36315.50, y=63.00, z=-403.50], aco['Squid'/8747613, l='MpServer', x=-36370.72, y=55.34, z=-369.38], aco['Squid'/8745215, l='MpServer', x=-36291.81, y=57.97, z=-393.75], afw['Skeleton'/8745183, l='MpServer', x=-36323.50, y=28.00, z=-412.50], afw['Skeleton'/8745182, l='MpServer', x=-36324.50, y=28.00, z=-413.50], agj['Zombie'/8745208, l='MpServer', x=-36383.66, y=35.00, z=-470.66]]
	Retry entities: 0 total; []
	Server brand: Spigot
	Server type: Non-integrated multiplayer server
Stacktrace:
	at cen.a(SourceFile:308)
	at bsu.b(SourceFile:2252)
	at bsu.a(SourceFile:323)
	at net.minecraft.client.main.Main.main(SourceFile:120)
	at sun.reflect.NativeMethodAccessorImpl.invoke0(Native Method)
	at sun.reflect.NativeMethodAccessorImpl.invoke(NativeMethodAccessorImpl.java:62)
	at sun.reflect.DelegatingMethodAccessorImpl.invoke(DelegatingMethodAccessorImpl.java:43)
	at java.lang.reflect.Method.invoke(Method.java:483)
	at net.minecraft.launchwrapper.Launch.launch(Launch.java:135)
	at net.minecraft.launchwrapper.Launch.main(Launch.java:28)

-- System Details --
Details:
	Minecraft Version: 1.8
	Operating System: Linux (amd64) version 3.18.2-2-ARCH
	Java Version: 1.8.0_31, Oracle Corporation
	Java VM Version: OpenJDK 64-Bit Server VM (mixed mode), Oracle Corporation
	Memory: 120259648 bytes (114 MB) / 954728448 bytes (910 MB) up to 954728448 bytes (910 MB)
	Mod Pack: 1.8-SNAPSHOT-r365-b46-2015-01-25_23-01-16
	LiteLoader Mods: 2 loaded mod(s)
          - Uyjulian's X-ray Mod version 1
          - VoxelMap version 1.4.7
	LaunchWrapper: 10 active transformer(s)
          - Transformer: com.mumfrey.liteloader.transformers.event.EventProxyTransformer
          - Transformer: com.mumfrey.liteloader.launch.LiteLoaderTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.CrashReportTransformer
          - Transformer: com.uyjulian.minecraft.XrayMod.XrayModEventTransformer
          - Transformer: com.thevoxelbox.voxelmap.litemod.VoxelMapTransformer
          - Transformer: com.mumfrey.liteloader.transformers.event.EventTransformer
          - Transformer: com.mumfrey.liteloader.common.transformers.LiteLoaderPacketTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.LiteLoaderEventInjectionTransformer
          - Transformer: com.mumfrey.liteloader.client.transformers.MinecraftTransformer
          - Transformer: com.mumfrey.liteloader.transformers.event.json.ModEventInjectionTransformer
	JVM Flags: 1 total; -Xmx1G
	IntCache: cache: 0, tcache: 0, allocated: 13, tallocated: 95
	Launched Version: 1.8
	LWJGL: 2.9.1
	OpenGL: GeForce GTS 250/PCIe/SSE2 GL version 3.3.0 NVIDIA 340.65, NVIDIA Corporation
	GL Caps: Using GL 1.3 multitexturing.
Using GL 1.3 texture combiners.
Using framebuffer objects because OpenGL 3.0 is supported and separate blending is supported.
Shaders are available because OpenGL 2.1 is supported.
VBOs are available because OpenGL 1.5 is supported.

	Using VBOs: No
	Is Modded: Definitely; Client brand changed to 'LiteLoader'
	Type: Client (map_client.txt)
	Resource Packs: [Plast Pack.zip]
	Current Language: §eEnglish (§bColor§e)
	Profiler Position: N/A (disabled)
