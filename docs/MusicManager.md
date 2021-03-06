# Class "MusicManager"
## Constructors
### MusicManager () {: aria-label='Constructors' }
[ ](#){: .abp .tooltip .badge }
#### [MusicManager](../MusicManager) MusicManager ( ) {: .copyable aria-label='Constructors' }

Returns a [MusicManager](../MusicManager) object.

???- example "Example Code"
    Example usage:
    ```lua 
    MusicManager():Disable()
    
    ```
___ 
## Functions
### Crossfade () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Crossfade ( [MusicManager](../MusicManager) ID ) {: .copyable aria-label='Functions' }

___ 
### Disable () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Disable ( ) {: .copyable aria-label='Functions' }

___ 
### DisableLayer () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void DisableLayer ( ) {: .copyable aria-label='Functions' }

___ 
### Enable () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Enable ( ) {: .copyable aria-label='Functions' }

___ 
### EnableLayer () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void EnableLayer ( ) {: .copyable aria-label='Functions' }

___ 
### Fadein () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Fadein ( [MusicManager](../MusicManager) ID, float Volume ) {: .copyable aria-label='Functions' }

___ 
### Fadeout () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Fadeout ( ) {: .copyable aria-label='Functions' }

___ 
### GetCurrentMusicID () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### [MusicManager](../MusicManager) GetCurrentMusicID ( ) {: .copyable aria-label='Functions' }

___ 
### GetQueuedMusicID () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### [MusicManager](../MusicManager) GetQueuedMusicID ( ) {: .copyable aria-label='Functions' }
if nothing is queued, return the current music id 
___ 
### IsEnabled () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### boolean IsEnabled ( ) {: .copyable aria-label='Functions' }

___ 
### IsLayerEnabled () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### boolean IsLayerEnabled ( ) {: .copyable aria-label='Functions' }

___ 
### Pause () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Pause ( ) {: .copyable aria-label='Functions' }

___ 
### PitchSlide () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void PitchSlide ( float TargetPitch ) {: .copyable aria-label='Functions' }

___ 
### Play () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Play ( [MusicManager](../MusicManager) ID, float Volume ) {: .copyable aria-label='Functions' }

___ 
### Queue () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Queue ( [MusicManager](../MusicManager) ID ) {: .copyable aria-label='Functions' }

___ 
### ResetPitch () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void ResetPitch ( ) {: .copyable aria-label='Functions' }

___ 
### Resume () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void Resume ( ) {: .copyable aria-label='Functions' }

___ 
### UpdateVolume () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void UpdateVolume ( ) {: .copyable aria-label='Functions' }

This function sets the music volume to the volume defined in the options menu.
___ 
### VolumeSlide () {: aria-label='Functions' }
[ ](#){: .abp .tooltip .badge }
#### void VolumeSlide ( float TargetVolume ) {: .copyable aria-label='Functions' }

___ 
