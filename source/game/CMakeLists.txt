INCLUDE_DIRECTORIES (
    ${STAR_EXTERN_INCLUDES}
    ${STAR_CORE_INCLUDES}
    ${STAR_BASE_INCLUDES}
    ${STAR_PLATFORM_INCLUDES}
    ${STAR_GAME_INCLUDES}
  )

SET (star_game_HEADERS
    StarActorMovementController.hpp
    StarAiDatabase.hpp
    StarAiTypes.hpp
    StarAmbient.hpp
    StarAnimation.hpp
    StarArmorWearer.hpp
    StarBehaviorDatabase.hpp
    StarBehaviorState.hpp
    StarBiome.hpp
    StarBiomeDatabase.hpp
    StarBiomePlacement.hpp
    StarCelestialCoordinate.hpp
    StarCelestialDatabase.hpp
    StarCelestialGraphics.hpp
    StarCelestialParameters.hpp
    StarCelestialTypes.hpp
    StarChatAction.hpp
    StarChatProcessor.hpp
    StarChatTypes.hpp
    StarClientContext.hpp
    StarCodex.hpp
    StarCodexDatabase.hpp
    StarCollectionDatabase.hpp
    StarCollisionBlock.hpp
    StarCollisionGenerator.hpp
    StarCommandProcessor.hpp
    StarDamage.hpp
    StarDamageDatabase.hpp
    StarDamageManager.hpp
    StarDamageTypes.hpp
    StarDanceDatabase.hpp
    StarDrawable.hpp
    StarDungeonGenerator.hpp
    StarDungeonImagePart.hpp
    StarDungeonTMXPart.hpp
    StarEffectEmitter.hpp
    StarEffectSourceDatabase.hpp
    StarEmoteProcessor.hpp
    StarEntityFactory.hpp
    StarEntityMap.hpp
    StarEntityRendering.hpp
    StarEntityRenderingTypes.hpp
    StarEntitySplash.hpp
    StarFallingBlocksAgent.hpp
    StarForceRegions.hpp
    StarGameTimers.hpp
    StarGameTypes.hpp
    StarHumanoid.hpp
    StarImageMetadataDatabase.hpp
    StarInput.hpp
    StarInteractionTypes.hpp
    StarInterpolationTracker.hpp
    StarInventoryTypes.hpp
    StarItem.hpp
    StarItemBag.hpp
    StarItemDatabase.hpp
    StarItemDescriptor.hpp
    StarItemDrop.hpp
    StarItemRecipe.hpp
    StarLightSource.hpp
    StarLiquidsDatabase.hpp
    StarLiquidTypes.hpp
    StarMaterialDatabase.hpp
    StarMaterialRenderProfile.hpp
    StarMaterialTypes.hpp
    StarMicroDungeon.hpp
    StarMonster.hpp
    StarMonsterDatabase.hpp
    StarMovementController.hpp
    StarNameGenerator.hpp
    StarNetPackets.hpp
    StarNetPacketSocket.hpp
    StarNetworkedAnimator.hpp
    StarNpc.hpp
    StarNpcDatabase.hpp
    StarObject.hpp
    StarObjectDatabase.hpp
    StarParallax.hpp
    StarParticle.hpp
    StarParticleDatabase.hpp
    StarParticleManager.hpp
    StarPlant.hpp
    StarPlantDatabase.hpp
    StarPlantDrop.hpp
    StarPlatformerAStar.hpp
    StarPlatformerAStarTypes.hpp
    StarPlayer.hpp
    StarPlayerBlueprints.hpp
    StarPlayerCodexes.hpp
    StarPlayerCompanions.hpp
    StarPlayerDeployment.hpp
    StarPlayerFactory.hpp
    StarPlayerInventory.hpp
    StarPlayerLog.hpp
    StarPlayerStorage.hpp
    StarPlayerTech.hpp
    StarPlayerTypes.hpp
    StarPlayerUniverseMap.hpp
    StarProjectile.hpp
    StarProjectileDatabase.hpp
    StarQuestDescriptor.hpp
    StarQuestManager.hpp
    StarQuests.hpp
    StarQuestTemplateDatabase.hpp
    StarRadioMessageDatabase.hpp
    StarRoot.hpp
    StarRootLoader.hpp
    StarServerClientContext.hpp
    StarSky.hpp
    StarSkyParameters.hpp
    StarSkyRenderData.hpp
    StarSkyTypes.hpp
    StarSongbook.hpp
    StarSpawner.hpp
    StarSpawnTypeDatabase.hpp
    StarSpeciesDatabase.hpp
    StarStagehand.hpp
    StarStagehandDatabase.hpp
    StarStatCollection.hpp
    StarStatistics.hpp
    StarStatisticsDatabase.hpp
    StarStatSet.hpp
    StarStatusController.hpp
    StarStatusEffectDatabase.hpp
    StarStatusTypes.hpp
    StarStoredFunctions.hpp
    StarSystemWorld.hpp
    StarSystemWorldClient.hpp
    StarSystemWorldServer.hpp
    StarSystemWorldServerThread.hpp
    StarTeamClient.hpp
    StarTeamManager.hpp
    StarTechController.hpp
    StarTechDatabase.hpp
    StarTenantDatabase.hpp
    StarTerrainDatabase.hpp
    StarTileDamage.hpp
    StarTileDrawer.hpp
    StarTileModification.hpp
    StarTileSectorArray.hpp
    StarTilesetDatabase.hpp
    StarToolUser.hpp
    StarTreasure.hpp
    StarUniverseClient.hpp
    StarUniverseConnection.hpp
    StarUniverseServer.hpp
    StarUniverseSettings.hpp
    StarVehicle.hpp
    StarVehicleDatabase.hpp
    StarVersioningDatabase.hpp
    StarWarping.hpp
    StarWeather.hpp
    StarWeatherTypes.hpp
    StarWireProcessor.hpp
    StarWiring.hpp
    StarWorldCamera.hpp
    StarWorldClient.hpp
    StarWorldClientState.hpp
    StarWorldGeneration.hpp
    StarWorldImpl.hpp
    StarWorldLayout.hpp
    StarWorldParameters.hpp
    StarWorldRenderData.hpp
    StarWorldServer.hpp
    StarWorldServerThread.hpp
    StarWorldStorage.hpp
    StarWorldStructure.hpp
    StarWorldTemplate.hpp
    StarWorldTiles.hpp

    interfaces/StarAnchorableEntity.hpp
    interfaces/StarActivatableItem.hpp
    interfaces/StarAggressiveEntity.hpp
    interfaces/StarBeamItem.hpp
    interfaces/StarChattyEntity.hpp
    interfaces/StarContainerEntity.hpp
    interfaces/StarDamageBarEntity.hpp
    interfaces/StarDurabilityItem.hpp
    interfaces/StarEffectSourceItem.hpp
    interfaces/StarEmoteEntity.hpp
    interfaces/StarEntity.hpp
    interfaces/StarFireableItem.hpp
    interfaces/StarInteractiveEntity.hpp
    interfaces/StarLoungingEntities.hpp
    interfaces/StarNametagEntity.hpp
    interfaces/StarNonRotatedDrawablesItem.hpp
    interfaces/StarPhysicsEntity.hpp
    interfaces/StarPreviewTileTool.hpp
    interfaces/StarPointableItem.hpp
    interfaces/StarPortraitEntity.hpp
    interfaces/StarPreviewableItem.hpp
    interfaces/StarRenderableItem.hpp
    interfaces/StarScriptedEntity.hpp
    interfaces/StarStatusEffectEntity.hpp
    interfaces/StarStatusEffectItem.hpp
    interfaces/StarSwingableItem.hpp
    interfaces/StarTileEntity.hpp
    interfaces/StarToolUserEntity.hpp
    interfaces/StarToolUserItem.hpp
    interfaces/StarWarpTargetEntity.hpp
    interfaces/StarWireEntity.hpp
    interfaces/StarWorld.hpp

    items/StarActiveItem.hpp
    items/StarArmors.hpp
    items/StarAugmentItem.hpp
    items/StarBlueprintItem.hpp
    items/StarCodexItem.hpp
    items/StarCurrency.hpp
    items/StarConsumableItem.hpp
    items/StarInspectionTool.hpp
    items/StarInstrumentItem.hpp
    items/StarLiquidItem.hpp
    items/StarMaterialItem.hpp
    items/StarObjectItem.hpp
    items/StarThrownItem.hpp
    items/StarTools.hpp
    items/StarUnlockItem.hpp

    objects/StarContainerObject.hpp
    objects/StarFarmableObject.hpp
    objects/StarLoungeableObject.hpp
    objects/StarPhysicsObject.hpp
    objects/StarTeleporterObject.hpp

    scripting/StarCameraLuaBindings.hpp
    scripting/StarCelestialLuaBindings.hpp
    scripting/StarBehaviorLuaBindings.hpp
    scripting/StarConfigLuaBindings.hpp
    scripting/StarEntityLuaBindings.hpp
    scripting/StarFireableItemLuaBindings.hpp
    scripting/StarInputLuaBindings.hpp
    scripting/StarItemLuaBindings.hpp
    scripting/StarLuaActorMovementComponent.hpp
    scripting/StarLuaAnimationComponent.hpp
    scripting/StarLuaGameConverters.hpp
    scripting/StarLuaComponents.hpp
    scripting/StarLuaRoot.hpp
    scripting/StarMovementControllerLuaBindings.hpp
    scripting/StarNetworkedAnimatorLuaBindings.hpp
    scripting/StarPlayerLuaBindings.hpp
    scripting/StarRootLuaBindings.hpp
    scripting/StarScriptedAnimatorLuaBindings.hpp
    scripting/StarSongbookLuaBindings.hpp
    scripting/StarStatusControllerLuaBindings.hpp
    scripting/StarTeamClientLuaBindings.hpp
    scripting/StarWorldLuaBindings.hpp
    scripting/StarUniverseServerLuaBindings.hpp
    scripting/StarScriptableThread.hpp

    terrain/StarCacheSelector.hpp
    terrain/StarConstantSelector.hpp
    terrain/StarDisplacementSelector.hpp
    terrain/StarFlatSurfaceSelector.hpp
    terrain/StarIslandSurfaceSelector.hpp
    terrain/StarKarstCave.hpp
    terrain/StarMaxSelector.hpp
    terrain/StarMinMaxSelector.hpp
    terrain/StarMixSelector.hpp
    terrain/StarPerlinSelector.hpp
    terrain/StarRidgeBlocksSelector.hpp
    terrain/StarRotateSelector.hpp
    terrain/StarWormCave.hpp
  )

SET (star_game_SOURCES
    StarActorMovementController.cpp
    StarAiDatabase.cpp
    StarAiTypes.cpp
    StarAmbient.cpp
    StarAnimation.cpp
    StarArmorWearer.cpp
    StarBehaviorDatabase.cpp
    StarBehaviorState.cpp
    StarBiome.cpp
    StarBiomeDatabase.cpp
    StarBiomePlacement.cpp
    StarCelestialCoordinate.cpp
    StarCelestialDatabase.cpp
    StarCelestialGraphics.cpp
    StarCelestialParameters.cpp
    StarCelestialTypes.cpp
    StarChatAction.cpp
    StarChatProcessor.cpp
    StarChatTypes.cpp
    StarClientContext.cpp
    StarCodex.cpp
    StarCodexDatabase.cpp
    StarCollectionDatabase.cpp
    StarCollisionBlock.cpp
    StarCollisionGenerator.cpp
    StarCommandProcessor.cpp
    StarDamage.cpp
    StarDamageDatabase.cpp
    StarDamageManager.cpp
    StarDamageTypes.cpp
    StarDanceDatabase.cpp
    StarDrawable.cpp
    StarDungeonGenerator.cpp
    StarDungeonImagePart.cpp
    StarDungeonTMXPart.cpp
    StarEffectEmitter.cpp
    StarEffectSourceDatabase.cpp
    StarEmoteProcessor.cpp
    StarEntityFactory.cpp
    StarEntityMap.cpp
    StarEntityRendering.cpp
    StarEntityRenderingTypes.cpp
    StarEntitySplash.cpp
    StarFallingBlocksAgent.cpp
    StarForceRegions.cpp
    StarGameTimers.cpp
    StarGameTypes.cpp
    StarHumanoid.cpp
    StarImageMetadataDatabase.cpp
    StarInput.cpp
    StarInteractionTypes.cpp
    StarInterpolationTracker.cpp
    StarInventoryTypes.cpp
    StarItem.cpp
    StarItemBag.cpp
    StarItemDatabase.cpp
    StarItemDescriptor.cpp
    StarItemDrop.cpp
    StarItemRecipe.cpp
    StarLightSource.cpp
    StarLiquidsDatabase.cpp
    StarLiquidTypes.cpp
    StarMaterialDatabase.cpp
    StarMaterialRenderProfile.cpp
    StarMicroDungeon.cpp
    StarMonster.cpp
    StarMonsterDatabase.cpp
    StarMovementController.cpp
    StarNameGenerator.cpp
    StarNetPackets.cpp
    StarNetPacketSocket.cpp
    StarNetworkedAnimator.cpp
    StarNpc.cpp
    StarNpcDatabase.cpp
    StarObject.cpp
    StarObjectDatabase.cpp
    StarParallax.cpp
    StarParticle.cpp
    StarParticleDatabase.cpp
    StarParticleManager.cpp
    StarPlant.cpp
    StarPlantDatabase.cpp
    StarPlantDrop.cpp
    StarPlatformerAStar.cpp
    StarPlatformerAStarTypes.cpp
    StarPlayer.cpp
    StarPlayerBlueprints.cpp
    StarPlayerCodexes.cpp
    StarPlayerCompanions.cpp
    StarPlayerDeployment.cpp
    StarPlayerFactory.cpp
    StarPlayerInventory.cpp
    StarPlayerLog.cpp
    StarPlayerStorage.cpp
    StarPlayerTech.cpp
    StarPlayerTypes.cpp
    StarPlayerUniverseMap.cpp
    StarProjectile.cpp
    StarProjectileDatabase.cpp
    StarQuestDescriptor.cpp
    StarQuestManager.cpp
    StarQuests.cpp
    StarQuestTemplateDatabase.cpp
    StarRadioMessageDatabase.cpp
    StarRoot.cpp
    StarRootLoader.cpp
    StarServerClientContext.cpp
    StarSky.cpp
    StarSkyParameters.cpp
    StarSkyRenderData.cpp
    StarSkyTypes.cpp
    StarSongbook.cpp
    StarSpawner.cpp
    StarSpawnTypeDatabase.cpp
    StarSpeciesDatabase.cpp
    StarStagehand.cpp
    StarStagehandDatabase.cpp
    StarStatCollection.cpp
    StarStatistics.cpp
    StarStatisticsDatabase.cpp
    StarStatSet.cpp
    StarStatusController.cpp
    StarStatusEffectDatabase.cpp
    StarStatusTypes.cpp
    StarStoredFunctions.cpp
    StarSystemWorld.cpp
    StarSystemWorldClient.cpp
    StarSystemWorldServer.cpp
    StarSystemWorldServerThread.cpp
    StarTeamClient.cpp
    StarTeamManager.cpp
    StarTechController.cpp
    StarTechDatabase.cpp
    StarTenantDatabase.cpp
    StarTerrainDatabase.cpp
    StarTileDamage.cpp
    StarTileDrawer.cpp
    StarTileModification.cpp
    StarTilesetDatabase.cpp
    StarToolUser.cpp
    StarTreasure.cpp
    StarUniverseClient.cpp
    StarUniverseConnection.cpp
    StarUniverseServer.cpp
    StarUniverseSettings.cpp
    StarVehicle.cpp
    StarVehicleDatabase.cpp
    StarVersioningDatabase.cpp
    StarWarping.cpp
    StarWeather.cpp
    StarWeatherTypes.cpp
    StarWireProcessor.cpp
    StarWiring.cpp
    StarWorldCamera.cpp
    StarWorldClient.cpp
    StarWorldClientState.cpp
    StarWorldGeneration.cpp
    StarWorldLayout.cpp
    StarWorldParameters.cpp
    StarWorldServer.cpp
    StarWorldServerThread.cpp
    StarWorldStorage.cpp
    StarWorldStructure.cpp
    StarWorldTemplate.cpp
    StarWorldTiles.cpp

    interfaces/StarAnchorableEntity.cpp
    interfaces/StarBeamItem.cpp
    interfaces/StarContainerEntity.cpp
    interfaces/StarDamageBarEntity.cpp
    interfaces/StarEntity.cpp
    interfaces/StarFireableItem.cpp
    interfaces/StarInteractiveEntity.cpp
    interfaces/StarLoungingEntities.cpp
    interfaces/StarPhysicsEntity.cpp
    interfaces/StarPointableItem.cpp
    interfaces/StarSwingableItem.cpp
    interfaces/StarTileEntity.cpp
    interfaces/StarToolUserItem.cpp
    interfaces/StarWorld.cpp

    items/StarActiveItem.cpp
    items/StarArmors.cpp
    items/StarAugmentItem.cpp
    items/StarBlueprintItem.cpp
    items/StarCodexItem.cpp
    items/StarCurrency.cpp
    items/StarConsumableItem.cpp
    items/StarInspectionTool.cpp
    items/StarInstrumentItem.cpp
    items/StarLiquidItem.cpp
    items/StarMaterialItem.cpp
    items/StarObjectItem.cpp
    items/StarThrownItem.cpp
    items/StarTools.cpp
    items/StarUnlockItem.cpp

    objects/StarContainerObject.cpp
    objects/StarFarmableObject.cpp
    objects/StarLoungeableObject.cpp
    objects/StarPhysicsObject.cpp
    objects/StarTeleporterObject.cpp

    scripting/StarCameraLuaBindings.cpp
    scripting/StarCelestialLuaBindings.cpp
    scripting/StarBehaviorLuaBindings.cpp
    scripting/StarConfigLuaBindings.cpp
    scripting/StarEntityLuaBindings.cpp
    scripting/StarFireableItemLuaBindings.cpp
    scripting/StarInputLuaBindings.cpp
    scripting/StarItemLuaBindings.cpp
    scripting/StarLuaComponents.cpp
    scripting/StarLuaGameConverters.cpp
    scripting/StarLuaRoot.cpp
    scripting/StarMovementControllerLuaBindings.cpp
    scripting/StarNetworkedAnimatorLuaBindings.cpp
    scripting/StarPlayerLuaBindings.cpp
    scripting/StarRootLuaBindings.cpp
    scripting/StarScriptedAnimatorLuaBindings.cpp
    scripting/StarSongbookLuaBindings.cpp
    scripting/StarStatusControllerLuaBindings.cpp
    scripting/StarTeamClientLuaBindings.cpp
    scripting/StarWorldLuaBindings.cpp
    scripting/StarUniverseServerLuaBindings.cpp
    scripting/StarScriptableThread.cpp

    terrain/StarCacheSelector.cpp
    terrain/StarConstantSelector.cpp
    terrain/StarDisplacementSelector.cpp
    terrain/StarFlatSurfaceSelector.cpp
    terrain/StarIslandSurfaceSelector.cpp
    terrain/StarKarstCave.cpp
    terrain/StarMaxSelector.cpp
    terrain/StarMinMaxSelector.cpp
    terrain/StarMixSelector.cpp
    terrain/StarPerlinSelector.cpp
    terrain/StarRidgeBlocksSelector.cpp
    terrain/StarRotateSelector.cpp
    terrain/StarWormCave.cpp
  )

ADD_LIBRARY (star_game OBJECT ${star_game_SOURCES} ${star_game_HEADERS})

IF(STAR_PRECOMPILED_HEADERS)
  TARGET_PRECOMPILE_HEADERS (star_game REUSE_FROM star_core)
ENDIF()
