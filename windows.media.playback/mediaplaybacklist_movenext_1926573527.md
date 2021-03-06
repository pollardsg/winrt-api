---
-api-id: M:Windows.Media.Playback.MediaPlaybackList.MoveNext
-api-type: winrt method
---

<!-- Method syntax
public Windows.Media.Playback.MediaPlaybackItem MoveNext()
-->

# Windows.Media.Playback.MediaPlaybackList.MoveNext

## -description
Changes the current item of the [MediaPlaybackList](mediaplaybacklist.md) to the next item in the list.

## -returns
The new current [MediaPlaybackItem](mediaplaybackitem.md).

## -remarks
This current item of the [MediaPlaybackList](mediaplaybacklist.md) can't be changed while a [MediaPlaybackItem](mediaplaybackitem.md) with [CanSkip](mediaplaybackitem_canskip.md) set to false is playing. Attempting to do so will cause an exception to be thrown.

## -examples

## -see-also
