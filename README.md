# Valorant Cheat — Safe Overlay

Download: soon

Overlay-only Valorant cheat. Vanguard is strict, so the build stays external and keeps its footprint small.

## Safety model

Nothing is injected into the client. The loader reads state through a handle and paints an overlay window. The aim curve is deliberately soft so killcams stay believable.

## Modules

### Aim

| Parameter | Default | Range |
| --- | --- | --- |
| fov | 6 | 1-20 |
| smooth | 4.5 | 1-12 |
| bone | chest | head/chest |
| visible | on | on/off |
| mode | hold | hold/toggle |

Head bone is only worth it indoors. Outdoors the chest bone keeps tracking calm.

### ESP

Boxes, skeleton, health, distance, team colors and visibility colors. Range cap 400 m. Skeleton off is a good default, it is noisy on small monitors.

### Radar

Minimap widget with arrows, scale 55-140%, range up to 600 m, opacity adjustable.

### Triggerbot

Delay 38 ms, zone 3 px, visible only. Below 25 ms looks robotic on killcams.

## Streamproof

On by default. Capture with game capture so OBS does not pick up the overlay.

## First session

1. Run the loader as administrator before the match
2. Start Valorant
3. INSERT, load `legit`
4. Play one unrated

Do not attach mid-match, Vanguard handles late attach worse than a clean start.

## Troubleshooting

| Symptom | Fix |
| --- | --- |
| overlay missing | windowed fullscreen |
| menu dead | admin rights |
| aim sticky | smoothing up one step |
| capture black | game capture plus streamproof |

## FAQ

**Does it touch Vanguard?** No, external only.

**Free?** Yes, no key.

**Works after patch?** Offsets need a new build after big updates.

## Compatibility

Windows 10/11, Riot Client, 16:9 and 21:9, DPI 150%.

Use a spare account for the first hour after a fresh build.
