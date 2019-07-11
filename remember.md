## shortcuts

- m/M - move/link selection to collection
- C-a - apply transformation; Also in `Object->Apply`
- C-\` - start fp mode when in Camera mode; Also in `View->Navigation`
- F3 - search for an action
- . - change pivot point
- A-m - merge faces,edges,vertices

## lights

- 3 point light rig - group in one collection with camera, <C-p> to parent lights to camera

## camera

- two basic modes of setting up camera position:
  - fp - first person mode
  - lock camera to view (N -> View lock)

## modeling

- loose geometry causes problems when exporting; in bigger models also when rendering
- you can add multiple mesh objects into one mesh object when in edit mode.
  This allows to keep them together, scale them with common pivot point, apply 
  material separately
- it is possible to e.g. scale multiple faces at once with pivot point set to individual
- when filling (F) first try in simple steps (like two edges)
- to remove duplicates/doubles use `Mesh->Clean up->Merge by distance` (A-m)
