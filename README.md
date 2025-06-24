# $̶$̶$̶-̶_̶_̶
___

# How to use place Filter

1. Add _PlaceFilter after the Fast Flag name.
2. Add a semicolon after the Value (;). Examples: True;, 1;.
3. Include a Place ID after the semicolon. Examples: True;4483381587, 1;4483381587.
4. Your configuration is complete.


# Quality Of Life

*Faster preloading*

```
{
    "DFIntNumAssetsMaxToPreload": "9999999",
    "DFIntAssetPreloading": "9999999"
}
```

*Limits lighting changes*

```
{
    "FIntRenderLocalLightUpdatesMax": "8",
    "FIntRenderLocalLightUpdatesMin": "6"
}
```
*Remove in-game advertisements*

```
{
    "FFlagAdServiceEnabled": "False"
}
```

*Disable telemetry*

```
{
    "FFlagDebugDisableTelemetryEphemeralCounter": "True",
    "FFlagDebugDisableTelemetryEphemeralStat": "True",
    "FFlagDebugDisableTelemetryEventIngest": "True",
    "FFlagDebugDisableTelemetryPoint": "True",
    "FFlagDebugDisableTelemetryV2Counter": "True",
    "FFlagDebugDisableTelemetryV2Event": "True",
    "FFlagDebugDisableTelemetryV2Stat": "True"
}
```

*Disable shadows*

```
{
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647"
}
```

*Reduce avatar particles in first person*

```
{
    "FFlagUserHideCharacterParticlesInFirstPerson": "True"
}
```

*Smoother terrain*

```
{
    "FFlagDebugRenderingSetDeterministic": "True"
}
```

*Disable player shadows*

```
{
    "FIntRenderShadowIntensity": "0"
}
```

*5 Decimal digits limit for camera sensitivty*

```
{
    "FFlagFixSensitivityTextPrecision": "False"
}
```

*Disable voicechat*

```
{
    "DFFlagVoiceChat4": "False"
}
```

*Disable dynamic head animations*

```
{
    "DFIntAnimationLodFacsDistanceMin": "0",
    "DFIntAnimationLodFacsDistanceMax": "0",
    "DFIntAnimationLodFacsVisibilityDenominator": "0"
}
```

*Automatically unmute your mic when you join*

__(This is for vociechat)__

```
{
    "FFlagDebugDefaultChannelStartMuted": "False"
}
```

*Change zoom out limit*

```
{
    "FIntCameraMaxZoomDistance": "9999"
}
```

*Quick game launching*

```
{
    "FFlagEnableQuickGameLaunch": "True"
}
```

*Display your fps*

```
{
	"FFlagDebugDisplayFPS": "True"
}
```

*Stop purchase prompts*

```
{
	"DFFlagOrder66": "True"
}
```

*Accessory adjustment in roblox player beta*

```
{
"FFlagAXAccessoryAdjustmentIXPEnabledForAll": "True",
"FFlagAccessoryAdjustmentEnabled5": "True"
}
```

# Physics related FFlags

*Tool desync*

```
{
    "DFIntSimBlockLargeLocalToolWeldManipulationsThreshold": "-1"
}
```

*Slide on terrain*

```
{
    "DFIntSmoothTerrainPhysicsRayAabbSlop": "-9999"
}
```

*Weird movement #1*

```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

*Weird movement #2*

```
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```

*Weird movement #3*

```
{
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1"
}
```

*Weird movement #4*

```
{
    "FFlagSimAdaptiveTimesteppingDefault2": "True",
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "DFFlagSimHumanoidTimestepModelUpdate": "True"
}
```

*Weird movement #5*

```
{
    "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
    "FIntPGSAngularDampingPermilPersecond": "0",
    "DFIntMaxAltitudePDHipHeightPercent": "-100",
    "DFFlagSimHumanoidPhysics": "True"
}
```

*Wall glide*

```
{
    "DFIntMaximumUnstickForceInGs": "-10"
}
```

*No animation*

__(Only shown on the servers side)__

```
{
    "DFIntReplicatorAnimationTrackLimitPerAnimator": "-1"
}
```

*Fling unanchored objects*

__(- Causes the objects to go upwards and + causes the objects to go downwards)__

```
{
    "DFIntSolidFloorPercentForceApplication": "-1000",
    "DFIntNonSolidFloorPercentForceApplication": "-5000"
}
```

*Max raycast distance*

__(Breaks leg collision from -2 to inf, Kind of breaks camera on values above 3 and Noclip camera on 3)__

```
{
    "DFIntRaycastMaxDistance": "3"
}
```

*Disable touch events*

```
{
    "DFIntTouchSenderMaxBandwidthBps": "-1"
}
```

*Drive cars slow*

```
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "0"
}
```

*Invisibility #1*

__(Stops the physics requests from your character sending to the server, This causes your character on the server's client to stop moving whilst being able to move on your client)__

```
{
    "DFIntS2PhysicsSenderRate": "-30"
}
```

*Invisibility #2*

__(Freezes your character at the position 0, 0, 0 on the server's client)__

```
{
    "DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "10"
}
```

*Invisibility #3*

__(Basically the same as the first one but you can get toppled over by other people on the server's client)__

```
{
    "DFIntPhysicsSenderMaxBandwidthBps": "1",
    "DFIntPhysicsSenderMaxBandwidthBpsScaling": "0"
}
```

*Slow motion*

```
{
    "DFIntMaxMissedWorldStepsRemembered": "1"
}
```

*Warp*

__(This is too confusing to explain though it does have to do with tab glitching)__

```
{
    "DFIntMaxMissedWorldStepsRemembered": "1000"
}
```

*Mesh noclip*

```
{
    "DFIntPhysicsDecompForceUpgradeVersion": "1500"
}
```

*Better network ownership*

```
{
    "DFIntMinClientSimulationRadius": "2147000000",
    "DFIntMinimalSimRadiusBuffer": "2147000000",
    "DFIntMaxClientSimulationRadius": "2147000000"
}
```

*Break most glitches*

```
{ 
"DFFlagSimHumanoidPhysics": "True"
}
```

*Breaks physics*

```
{
  "FFlagLuauSolverV2": "True",
  "DFIntMaximumFreefallMoveTimeInTenths": "1000",
  "FIntInterpolationAwareTargetTimeLerpHundredth": "110",
  "FFlagReplicateAnimationLooped": "False",
}
```

*Become short*

```
{
"DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "5",
"DFIntMaxAltitudePDHipHeightPercent": "-10",
"DFIntNewPDAltitudeNoForceZonePercent": "-5"
} 
```

*weird physics*

```
{
  "DFIntMaxAltitudePDHipHeightPercent": "-1000",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-200000",
  "SFFlagBulletContactBreakOrthogonalThresholdPercent": "2147483647",
}
```

*No velocity*

```
{
"DFIntGameNetPVHeaderTranslationZeroCutoffExponent": "3",
"DFIntGameNetPVHeaderRotationalVelocityZeroCutoffExponent": "3",
"DFIntGameNetPVHeaderLinearVelocityZeroCutoffExponent": "3",
"DFIntGameNetPVHeaderRotationOrientIdToleranceExponent": "0"
}
```

*Ctrl+f7 desync*

```
{
"DFFlagDebugEnableInterpThrottle": "true"
}
```

*Weird tp*

```
{
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-2147483648"
}
```

*Ragdoll yourself*

```
{
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-999999",
  "FIntPGSAngularDampingPermilPersecond": "0"
}
```

*No knockback*

```
{
    "DFIntPhysicsImprovedCyclicExecutiveThrottleThresholdTenth": "-1",
    "DFIntGameNetLocalSpaceMaxSendIndex": "100000"
}
```

*Purely broken movement #1*

```
{
  "DFIntRaycastMaxDistance": "-110",
  "DFIntBulletContactBreakOrthogonalThresholdPercent": "-2147483647",
  "DFIntMaximumFreefallMoveTimeInTenths": "0",
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1"
}
```
*Purely broken movement #2*

```
{
 "DFIntBulletContactBreakOrthogonalThresholdPercent": "-2147483648",
 "DFIntGameNetLocalSpaceMaxSendIndex": "100000",
 "DFIntMaxAltitudePDHipHeightPercent": "-5000",
 "DFIntMaxMissedWorldStepsRemembered": "1000",
"DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-10000000",
 "DFIntSmoothTerrainPhysicsRayAabbSlop": "-2147483648",
 "SFFlagBulletContactBreakOrthogonalThresholdPercent": "-2147483647"
}
```

*???*

```
{
  "DFIntSimAdaptiveHumanoidPDControllerSubstepMultiplier": "-1",
  "SFFlagBulletContactBreakOrthogonalThresholdPercent": "-2147483647",
  "DFIntMaxAltitudePDStickHipHeightPercent": "2147483647"
}
```

*Prevents remote events from running*

```
{
"DFIntRemoteEventSingleInvocationSizeLimit": "1"
}
```

# Visusals

*Semi full-bright*

__(A bit buggy)__

```
{
    "FFlagFastGPULightCulling3": "True",
    "FIntRenderShadowIntensity": "0",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "2147483647",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "2147483647",
    "FFlagNewLightAttenuation": "True",
    "FIntRenderShadowmapBias": "-1",
    "DFFlagDebugPauseVoxelizer": "True"
}
```

*Outline hitboxes #1*

```
{
    "DFFlagDebugDrawBroadPhaseAABBs": "True"
}
```

*Outline hitboxes #2*

```
{
    "DFFlagDebugDrawBvhNodes": "True"
}
```

*Buggy z-plane camera*

```
{
    "FIntCameraFarZPlane": "1"
}
```

*Adds a in-game ui that shows what your character is touching*

```
{
    "FFlagDebugHumanoidRendering": "True"
}
```

*X-ray #1*

```
{
    "DFIntCullFactorPixelThresholdMainViewHighQuality": "10000",
    "DFIntCullFactorPixelThresholdMainViewLowQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapHighQuality": "10000",
    "DFIntCullFactorPixelThresholdShadowMapLowQuality": "10000"
}
```

*X-ray #2*

```
{
  "DFIntCullFactorPixelThresholdMainViewHighQuality": "1250",
  "DFIntCullFactorPixelThresholdMainViewLowQuality": "1250",
  "DFIntCullFactorPixelThresholdShadowMapHighQuality": "1250",
  "DFIntCullFactorPixelThresholdShadowMapLowQuality": "1250",
  "DFIntDebugFRMQualityLevelOverride": "1"
}
```

*Turn the sky gray*

```
{
    "FFlagDebugSkyGray": "True"
}
```

*Really low quality*

```
{
    "DFIntDebugDynamicRenderKiloPixels": "1"
}
```

# Presets

*High quality graphics, lighting etc.*

```
{
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3",
    "DFIntCanHideGuiGroupId":	"32380007",
    "DFIntTaskSchedulerTargetFps": "999",
    "FFlagDebugForceFutureIsBrightPhase3": "True",
    "FFlagDebugGraphicsPreferD3D11": "True",
    "FFlagRenderInitShadowmaps": "true",
    "FFlagDebugSkyGray": "True",
    "FFlagDebugRenderingSetDeterministic": "True"
}
```

*Rtx*

```
{
    "FFlagDebugGraphicsPreferD3D11": "True",
    "FFlagDebugForceFutureIsBrightPhase3": "True",
    "FFlagDebugDeterministicParticles" : "True",
    "FFlagDebugRenderingSetDeterministic": "True",
    "DFFlagTextureQualityOverrideEnabled": "True",
    "DFIntTextureQualityOverride": "3",
    "FIntSSAO": "3",
    "FIntSSAOMipLevels": "3",
    "FFlagDebugSSAOForce": "True",
    "FFlagUseDeferredRendering": "True",
    "FFlagDebugEnableOctreeValidation": "True",
    "FFlagSimEnableDCD16": "True",
    "DFFlagESGamePerfMonitorEnabled": "True",
    "FFlagRenderUnifiedLighting10": "True",
    "FFlagUnifiedLightingBetaFeature": "True",
    "FFlagFRMRefactor": "True",
    "FFlagDebugRenderingSetDeterministic": "True"
}
```

*Better fps*

__(Makes your game look terrible)__

```
{
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FLogNetwork": "7",
  "DFIntTaskSchedulerTargetFps": "10000",
  "FFlagEnableV3MenuABTest3": "False",
  "FFlagFixGraphicsQuality": "True",
  "FFlagEnableInGameMenuModernization": "True",
  "DFFlagDisableDPIScale": "True",
  "FFlagEnableMenuControlsABTest": "False",
  "FFlagDisableNewIGMinDUA": "True",
  "FFlagEnableInGameMenuControls": "True",
  "DFIntCanHideGuiGroupId": "32380007",
  "DFIntAnimationLodFacsDistanceMin": "0",
  "DFIntCSGLevelOfDetailSwitchingDistance": " 1",
  "DFIntHttpCurlConnectionCacheSize": "134217728",
  "FIntFontSizePadding": "2",
  "DFFlagTextureQualityOverrideEnabled": "True",
  "FIntFullscreenTitleBarTriggerDelayMillis": "18000000",
  "DFFlagDebugPauseVoxelizer": "True",
  "FIntTerrainArraySliceSize": "0",
  "FIntRenderShadowIntensity": "0",
  "FFlagEnableInGameMenuChrome": "True",
  "FFlagDebugLightGridShowChunks": "False",
  "FStringPerformanceSendMeasurementAPISubdomain": "opt-out",
  "DFIntTextureQualityOverride": "0",
  "DFIntUserIdPlayerNameLifetimeSeconds": "86400",
  "FFlagDisablePostFx": "True",
  "DFIntCSGLevelOfDetailSwitchingDistanceL23": "3",
  "DFFlagEnableLightstepReporting2": "False",
  "FFlagDebugDisableTelemetryEphemeralCounter": "True",
  "FFlagNewLightAttenuation": "True",
  "FFlagEnableMenuModernizationABTest2": "False",
  "DFStringRobloxAnalyticsSubDomain": "opt-out",
  "DFFlagEnableGCapsHardwareTelemetry": "False",
  "DFStringTelegrafHTTPTransportUrl": "http://opt-out.roblox.com",
  "FFlagEnableSoundTelemetry": "False",
  "DFStringCrashUploadToBacktraceBaseUrl": "http://opt-out.roblox.com",
  "DFIntHardwareTelemetryHundredthsPercent": "0",
  "FIntEmotesAnimationsPerPlayerCacheSize": "16777216",
  "FIntFRMMinGrassDistance": "0",
  "DFFlagDebugRenderForceTechnologyVoxel": "True",
  "FIntDefaultMeshCacheSizeMB": "256",
  "FIntBootstrapperTelemetryReportingHundredthsPercentage": "0",
  "DFFlagGpuVsCpuBoundTelemetry": "False",
  "DFIntUserIdPlayerNameCacheSize": "33554432",
  "DFIntMegaReplicatorNetworkQualityProcessorUnit": "10",
  "FIntRenderLocalLightUpdatesMax": "1",
  "FFlagDebugSkyGray": "false",
  "DFIntCSGLevelOfDetailSwitchingDistanceL34": "4",
  "FFlagChatTranslationSettingEnabled3": "false",
  "FFlagTaskSchedulerLimitTargetFpsTo2402": "false",
  "DFIntMaxProcessPacketsJobScaling": "10000",
  "DFFlagAudioDeviceTelemetry": "False",
  "FIntRenderLocalLightUpdatesMin": "1",
  "FIntLmsClientRollout2": "0",
  "FFlagLuaAppSystemBar": "False",
  "FIntRakNetResendBufferArrayLength": "1024",
  "FFlagPreloadAllFonts": "True",
  "DFStringHttpPointsReporterUrl": "http://opt-out.roblox.com",
  "FIntFRMMaxGrassDistance": "0",
  "DFIntLargePacketQueueSizeCutoffMB": "1000",
  "FFlagGpuGeometryManager7": "True",
  "DFStringRobloxAnalyticsURL": "http://opt-out.roblox.com",
  "DFFlagQueueDataPingFromSendData": "True",
  "FFlagEnableQuickGameLaunch": "False",
  "FFlagTopBarUseNewBadge": "True",
  "FFlagAnimationClipMemCacheEnabled": "True",
  "FFlagFastGPULightCulling3": "True",
  "DFIntRakNetNakResendDelayRttPercent": "50",
  "DFIntAnimationLodFacsDistanceMax": "0",
  "DFIntReportRecordingDeviceInfoRateHundredthsPercentage": "0",
  "FFlagOptimizeServerTickRate": "True",
  "FFlagEnableInGameMenuV3": "True",
  "FFlagDebugDisableTelemetryV2Counter": "True",
  "FFlagBatchAssetApi": "True",
  "DFIntAnimationLodFacsVisibilityDenominator": "0",
  "DFIntCSGLevelOfDetailSwitchingDistanceL12": "2",
  "FStringErrorUploadToBacktraceBaseUrl": "http://opt-out.roblox.com",
  "FFlagRenderGpuTextureCompressor": "True",
  "DFFlagBatchAssetApiNoFallbackOnFail": "False",
  "FFlagEnableMenuModernizationABTest": "False",
  "DFIntMaxProcessPacketsStepsPerCyclic": "5000",
  "FIntUITextureMaxRenderTextureSize": "1024",
  "FFlagPreloadTextureItemsOption4": "True",
  "DFIntReportOutputDeviceInfoRateHundredthsPercentage": "0",
  "DFStringAltTelegrafHTTPTransportUrl": "http://opt-out.roblox.com",
  "FFlagDebugDisableTelemetryPoint": "True",
  "DFStringAltHttpPointsReporterUrl": "http://opt-out.roblox.com",
  "DFFlagEnableFmodErrorsTelemetry": "False",
  "DFIntMaxProcessPacketsStepsAccumulated": "0",
  "FFlagDontCreatePingJob": "True",
  "FFlagLuaAppExitModalDoNotShow": "True",
  "FIntTerrainOTAMaxTextureSize": "1024",
  "FFlagCoreGuiTypeSelfViewPresent": "False",
  "FIntRenderGrassHeightScaler": "0",
  "DFIntGoogleAnalyticsLoadPlayerHundredth": "0",
  "DFIntServerTickRate": "60",
  "FFlagDebugDisableTelemetryEphemeralStat": "True",
  "FIntRenderGrassDetailStrands": "0",
  "FFlagDebugDisableTelemetryV2Event": "True",
  "DFIntConnectionMTUSize": "1472",
  "DFIntRakNetNakResendDelayMsMax": "5",
  "DFFlagDebugAnalyticsSendUserId": "False",
  "DFFlagSimReportCPUInfo": "False",
  "FFlagDebugDisableTelemetryV2Stat": "True",
  "FFlagCommitToGraphicsQualityFix": "True",
  "DFIntRaknetBandwidthPingSendEveryXSeconds": "1",
  "FFlagDebugDisableTelemetryEventIngest": "True",
  "DFStringAnalyticsEventStreamUrlEndpoint": "opt-out",
  "FFlagReconnectDisabled": "True",
  "DFFlagRakNetUseSlidingWindow4": "True",
  "FIntMeshContentProviderForceCacheSize": "268435456",
  "DFIntRakNetNakResendDelayMs": "1",
  "DFIntRakNetResendRttMultiple": "1",
  "FIntRakNetDatagramMessageIdArrayLength": "1024",
  "DFIntOptimizePingThreshold": "50",
  "DFIntDebugFRMQualityLevelOverride": "1",
  "DFIntLightstepHTTPTransportHundredthsPercent2": "0",
  "DFFlagEnableHardwareTelemetry": "False",
  "FIntRenderShadowmapBias": "0",
  "FFlagLuaAppExitModal2": "False",
  "FFlagInGameMenuV1FullScreenTitleBar": "False",
  "FIntDebugForceMSAASamples": "1",
  "DFIntS2PhysicsRenderRate": "200",
  "DFIntS2PhysicsUpdateRate": "200",
  "DFIntServerPhysicsUpdateRate": "200",
  "FFlagAdServiceEnabled": "False",
  "FFlagEnableAccessibilitySettingsEffectsInCoreScripts2": "True",
  "FFlagGameBasicSettingsFramerateCap5": "false",
  "DFIntRakNetLoopMs": "1",
  "DFIntWaitOnRecvFromLoopEndedMS": "5",
  "FFlagEnableAccessibilitySettingsEffectsInExperienceChat": "True",
  "DFIntRaknetBandwidthInfluxHundredthsPercentageV2": "10000",
  "DFIntCodecMaxIncomingPackets": "5",
  "DFIntCodecMaxOutgoingFrames": "10000",
  "FFlagMSRefactor5": "False",
  "FFlagEnableAccessibilitySettingsInExperienceMenu2": "True",
  "FFlagEnableChromePinnedChat": "True",
  "DFFlagDebugPerfMode": "True",
  "DFIntMaxFrameBufferSize": "4",
  "FFlagEnableAccessibilitySettingsAPIV2": "True",
  "FFlagDebugGraphicsDisableMetal": "true",
  "FIntRobloxGuiBlurIntensity": "0",
  "DFIntWaitOnUpdateNetworkLoopEndedMS": "5"
}
```

*Lowers trigger delay*

```
{
"FIntActivatedCountTimerMSKeyboard":"0",
"FIntActivatedCountTimerMSMouse":"0"
}
```

*Faster tsb dashes*

```
{
  "FLogNetwork": "7",
  "FFlagHandleAltEnterFullscreenManually": "False",
  "FIntFullscreenTitleBarTriggerDelayMillis": "3600000",
  "DFIntCanHideGuiGroupId": "32380007",
  "DFIntPhysicsAnalyticsHighFrequencyIntervalSec": "20",
  "DFIntMaxFrameBufferSize": "4",
  "DFIntS2PhysicsSenderRate": "250",
  "DFIntDebugSimPrimalStiffness": "0",
  "FFlagLuauSolverV2": "True",
  "DFIntMaximumFreefallMoveTimeInTenths": "1000",
  "FIntInterpolationAwareTargetTimeLerpHundredth": "110",
  "FFlagDebugSimDefaultPrimalSolver": "True",
  "FFlagReplicateAnimationLooped": "False",
  "FFlagGraphicsFixMsaaInGuiScene": "True",
  "DFFlagSimSolverOptimizeLDLCache": "True",
  "FFlagEnableSceneAnalysis": "False",
  "DFIntGraphicsOptimizationModeMaxFrameTimeTargetMs": "20"
}
```

*Fix ping issue*

```
{
  "DFIntLargePacketQueueSizeCutoffMB": "1000",
  "DFIntMaxProcessPacketsJobScaling": "10000",
  "DFIntMaxProcessPacketsStepsAccumulated": "0",
  "DFIntMaxProcessPacketsStepsPerCyclic": "5000",
  "DFIntMegaReplicatorNetworkQualityProcessorUnit": "10",
  "DFIntRakNetClockDriftAdjustmentPerPingMillisecond": "100",
  "DFIntRaknetBandwidthInfluxHundredthsPercentageV2": "10000",
  "DFIntCodecMaxIncomingPackets": "100",
  "DFIntCodecMaxOutgoingFrames": "10000",
}
```

