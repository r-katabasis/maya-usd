list(APPEND scripts_src
    mayaUsdTranslatorImport.mel
    mayaUsdTranslatorExport.mel
    AEmayaUsdProxyShapeTemplate.mel
    mayaUsdMenu.mel
    mayaUsd_createStageFromFile.mel
    mayaUsd_createStageWithNewLayer.py
    mayaUsd_createStageFromAsset.mel
    mayaUsd_pluginUICreation.mel
    mayaUsd_pluginUIDeletion.mel
    mayaUsd_pluginBatchLoad.mel
    mayaUsd_pluginBatchUnload.mel
)

install(FILES ${scripts_src}
    DESTINATION ${INSTALL_DIR_SUFFIX}/scripts
)
