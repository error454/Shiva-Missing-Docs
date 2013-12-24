API Additions in ShiVa Version 1.9.2
====

## Animation

### Functions
```
getClipChannelCount
getClipChannelHasTrack
getClipChannelName
getObjectChannelUseTrack
getObjectChannelUseTrackFullPlaybackLevels
getObjectChannelUseTrackIncrementalUpdates
setObjectChannelUseTrack
setObjectChannelUseTrackFullPlaybackLevels
setObjectChannelUseTrackIncrementalUpdates
```

### Constants
```
kPlaybackBlendModeAdditive  
kTrackTypeRotation          
kTrackTypeScale             
kTrackTypeTranslation       
```

## Application

### Functions
```
getAudioListenerObject
getUseAverageFrameTime
setAudioListenerObject
setUseAverageFrameTime
```

### Constants
```
kDistantEnvironmentSendMethodPOST                     
kDistantEnvironmentSendMethodXML                      
kOptionAudioSpatializationEnabled                     
kOptionBakeAnimations                                 
kOptionCheckCachedPackFilesIntegrity          
kOptionDistantEnvironmentSendMethod                   
kOptionDynamicLightingMaxPixelLightsPerPass   
kOptionDynamicLightingMaxVertexLightsPerPass  
kOptionHomeButtonMenuAllowed                          
kOptionMaxDynamicFontSize                     
kOptionMaxJoypadsAllowed                              
kOptionMaxParticlesPerEmitter   
kOptionMeshSkinningMaxJointsPerVertex                 
kOptionNativeStringPoolSize                           
kOptionNetworkSocketTimeout                           
kOptionOffscreenRenderingBlitToScreen         
kOptionOffscreenRenderingBufferHeight         
kOptionOffscreenRenderingBufferWidth          
kOptionParticlesEnabled                               
kOptionParticlesRotationEnabled               
kOptionUseLowResolutionParticles              
kOptionUseOffscreenRendering                  
```

## Camera

### Functions
```
getRenderMapName
setFrustumMargins
setRenderMap
```

## Collider

### Functions
```
create
destroy
isAlwaysDisabled
isDisabledWhenObjectInactive 
setAlwaysDisabled
setDisabledWhenObjectInactive
```

## HUD

### Functions
```
enableListItemSelectionAt
enableOffscreenOutput
finishAction
finishAllActions
getComponentBackgroundImageFilteringMode
getContainerClipChildren
getListColumnWidthAt
getListFingerScrollingInertia
getTimer
getTimerTag
isComponentAspectInvariant
isComponentIgnoredByMouse
setComponentBackgroundImageFilteringMode
setContainerClipChildren
setListFingerScrollingInertia
setListItemChildAt
```

### Constants
```
kCommandTypeFinishAction                   
kFilteringModeBilinearNoMipmaps            
kFilteringModeNearestNoMipmaps             
```

## Input

### Functions
```
getJoypadBatteryLevel
isJoypadExtensionAttached
scanDevices
```

## Light

### Functions
```
getDynamicShadowsViewSpaceClipRectangle
setDynamic
setDynamicShadowsViewSpaceClipRectangle
```

## Log
```
enable
isEnabled
```

## Mesh

### Functions
```
setSubsetBoundingBox
setSubsetVertexNormals
setSubsetVertexPositions
setSubsetVertexTexCoords
```

## Object

### Functions
```
enableAIModel
enableZoneActivation
getReceivesCustomAIEventsWhenInactive
getRotationQuaternion
rotateQuaternion
rotateToQuaternion
setReceivesCustomAIEventsWhenInactive
setRotationQuaternion
```

### Constants
```
kControllerTypeAny
```

## Scene

### Functions
```
createActivationZone
destroyActivationZone
destroyAllActivationZones
enableActivationZone
getActivationZoneCount
getActivationZoneNameAt
getAmbientOcclusionColor
getAmbientOcclusionDepthBias
getAmbientOcclusionDistance
getAmbientOcclusionIntensity
getAmbientOcclusionSampleCount
getAnimationsFrameTimeFactor
getColorGradingFadeTime
getColorGradingFilteringMode
getColorGradingIntensity
getDynamicsFrameTimeFactor
getGammaCorrection
getParticlesFrameTimeFactor
getTrailsFrameTimeFactor
isActivationZoneEnabled
isPaused
sectorize
setActivationZoneExtents
setAmbientOcclusionColor
setAmbientOcclusionDepthBias
setAmbientOcclusionDistance
setAmbientOcclusionIntensity
setAmbientOcclusionSampleCount
setAnimationsFrameTimeFactor
setBackgroundPixelMap
setColorGradingFadeTime
setColorGradingFilteringMode
setColorGradingIntensity
setColorGradingTexture
setDynamicsFrameTimeFactor
setGammaCorrection
setParticlesFrameTimeFactor
setTrailsFrameTimeFactor
```

## SFX

### Functions
```
addParticleAttractorField
addParticleTurbulenceField
addParticleVortexField
getParticleAttractorFieldCount
getParticleAttractorFieldPointPosition
getParticleAttractorFieldShapeType
getParticleAttractorFieldStrength
getParticleEmitterCustomForce
getParticleEmitterInitialCountFactorAt
getParticleEmitterMaxCountLimitAt
getParticleEmitterNameAt
getParticleEmitterOpacityAt
getParticleEmitterUseCustomForce
getParticleTurbulenceFieldFrequency
getParticleTurbulenceFieldStrength
getParticleVortexFieldAxialDrop
getParticleVortexFieldAxialDropDamping
getParticleVortexFieldOrbitalSpeed
getParticleVortexFieldOrbitalSpeedDamping
getParticleVortexFieldRadialPull
getParticleVortexFieldRadialPullDamping
getParticleVortexFieldStrength
removeAllParticleAttractorFields
removeAllParticleTurbulenceFields
removeAllParticleVortexFields
removeParticleAttractorField
removeParticleTurbulenceField
removeParticleVortexField
setParticleAttractorFieldPointPosition
setParticleAttractorFieldStrength
setParticleEmitterCustomForce
setParticleEmitterInitialCountFactorAt
setParticleEmitterMaxCountLimitAt
setParticleEmitterOpacityAt
setParticleEmitterUseCustomForce
setParticleTurbulenceFieldFrequency
setParticleTurbulenceFieldStrength
setParticleVortexFieldAxialDrop
setParticleVortexFieldAxialDropDamping
setParticleVortexFieldOrbitalSpeed
setParticleVortexFieldOrbitalSpeedDamping
setParticleVortexFieldPosition
setParticleVortexFieldRadialPull
setParticleVortexFieldRadialPullDamping
setParticleVortexFieldStrength
```

### Constants
```
kShapeTypePoint
```

## Shape

### Functions
```
computeMeshSubsetVertexColors
createMeshSubsetVertexColorBuffer
destroyMeshSubsetVertexColorBuffer
getMeshSubsetMaterialFresnelOverride
getMeshSubsetVertexColor
getMeshSubsetVertexColorCount
isMeshSubsetVertexColorBufferDynamic
lockMeshSubsetVertexColorBuffer
overrideMeshMaterialFresnel
overrideMeshSubsetMaterialFresnel
overrideSkeletonJointRotationQuaternion
setMesh
setMeshSubsetVertexColor
setMeshSubsetVertexColorBufferDynamic
setMeshSubsetVertexColors
unlockMeshSubsetVertexColorBuffer
```

### Constants
```
kLockModeRead                    
kLockModeReadWrite               
kLockModeWrite                   
```

## Sound

### Functions
```
getSpatializationGain
```

### Constants
These constants don't seem to be usable in any existing API calls.  Perhaps a glimpse of things to come.
```
kReverbPresetAlley
kReverbPresetArena
kReverbPresetAuditorium
kReverbPresetBathRoom
kReverbPresetCarpetedHallway
kReverbPresetCave
kReverbPresetCity
kReverbPresetConcertHall
kReverbPresetDizzy
kReverbPresetDrugged
kReverbPresetForest
kReverbPresetGeneric
kReverbPresetHallway
kReverbPresetHangar
kReverbPresetLivingRoom
kReverbPresetMountains
kReverbPresetNone
kReverbPresetPaddedCell
kReverbPresetParkingLot
kReverbPresetPlain
kReverbPresetPsychotic
kReverbPresetQuarry
kReverbPresetRoom
kReverbPresetSewerPipe
kReverbPresetStoneCorridor
kReverbPresetStoneRoom
kReverbPresetUnderwater
```

## String

### Functions
```
encodeUTF8
```

## System

### Functions
```
getCurrentScreenPixelDensity
```

### Constants
```
kGPUCapabilityAmbientOcclusionFilterSupport        
kGPUCapabilityColorGradingFilterSupport          
kGPUCapabilityGammaFilterSupport                 
kGPUCapabilityOffscreenRenderingSupport            
kOSTypeFlash                                       
kOSTypeNaCl                                        
kOSTypeWinRT                                     
```

## User

### Functions
```
enableAIModel
```

### Constants
```
kResultErrorNotEnoughIndexNodes
```