# TABGSH
TABG Extension

Features:
Read the source.

Use MonoInjector64 with following parameters:
--target TotallyAccurateBattlegrounds.exe --dll TABGSH.dll --class CHLoader --method Load --namespace TABGSH

FAQ:

0. How do I start the hack?
A: Inject the compiled dll into the process using i.e. MonoInjector

1. Why is some code red underlined?
A: You need to add references first.

2. Where do I get the references from?
A: {Steam]\steamapps\common\TotallyAccurateBattlegrounds\TotallyAccurateBattlegrounds_Data\Managed

3. Why is it still red underlined?
A: Try to add them again, but this time, 1 dll after another.

4. Why does my game crashes after the update?
A: A function name changed, just readd the new dlls to the project and try to find the new function name with dnSpy or similar programs.

5. Why is it lagging when I try the hack in the shooting range?
A: I don't know

6. Why doesn't my name change after I pressed Change Name?
A: You can only change your name in the lobby.

7. Why can't I drop/throw spawned Items/Grenades?
A: Spawned items are spawned clientside only and are not synced online, if you find a way to spawn items, make a pull request or inform me at UC, thanks.
