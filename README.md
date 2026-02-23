# antd-dsfr

🚧

[AntD theme editor](https://ant.design/theme-editor)

[Documentation Apache Superset](https://superset.apache.org/docs/6.0.0/configuration/theming/#managing-themes-via-ui)

```python
FEATURE_FLAGS = {
  "ENABLE_UI_THEME_ADMINISTRATION": True
}
```

https://github.com/apache/superset/blob/cbb80f046279b1a58b745f3a91d0b1f1b29292a3/superset/config.py#L916

```json
{
  "token": {
    "brandLogoAlt": "Apache Superset DSFR",
    "brandLogoUrl": "https://superset5.lab.sspcloud.fr/static/assets/local/images/app_icon.png",
    "brandLogoHref": "/",
    "fontUrls": [
      "https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;600;700&display=swap",
      "https://fonts.googleapis.com/css2?family=JetBrains+Mono:wght@400;500&display=swap"
    ],
    "fontFamily": "Marianne, Roboto, -apple-system, BlinkMacSystemFont, sans-serif",
    "fontFamilyCode": "JetBrains Mono, Monaco, monospace",
    "transitionTiming": "0.3",
    "brandIconMaxWidth": "3",
    "fontSizeXS": "8",
    "fontSizeXXL": "28",
    "fontWeightNormal": "400",
    "fontWeightLight": "300",
    "fontWeightStrong": "500",
    "wireframe": false,
    "colorPrimary": "#000091",
    "colorInfo": "#000091",
    "colorError": "#ce0500",
    "colorSuccess": "#18753c",
    "colorWarning": "#b34000",
    "colorPrimaryHover": "#1212ff",
    "colorPrimaryActive": "#2323ff",
    "colorSuccessHover": "#27a959",
    "colorSuccessActive": "#2fc368",
    "colorWarningHover": "#ff6218",
    "colorWarningActive": "#ff7a55",
    "colorErrorHover": "#ff2725",
    "colorErrorActive": "#ff4140",
    "colorLink": "#000091",
    "colorLinkHover": "#1212ff",
    "colorLinkActive": "#2323ff",
    "colorSuccessText": "#18753c",
    "colorWarningText": "#ffffff",
    "colorWarningTextActive": "#ffffff",
    "colorWarningTextHover": "#ffffff",
    "colorErrorTextHover": "#ffffff",
    "colorErrorText": "#ffffff",
    "colorErrorTextActive": "#ffffff",
    "colorInfoTextHover": "#ffffff",
    "colorInfoText": "#ffffff",
    "colorInfoTextActive": "#ffffff",
    "colorInfoHover": "#98b4ff",
    "colorInfoActive": "#b4c7ff",
    "colorTextBase": "#3a3a3a"
  },
  "components": {
    "Button": {
      "borderRadius": 5,
      "borderRadiusSM": 5,
      "borderRadiusLG": 5,
      "textTextColor": "rgb(255,255,255)",
      "textTextActiveColor": "rgb(255,255,255)",
      "textTextHoverColor": "rgb(255,255,255)",
      "solidTextColor": "rgb(255,255,255)",
      "colorPrimaryText": "rgb(255,255,255)",
      "colorPrimaryTextActive": "rgb(255,255,255)",
      "colorPrimaryTextHover": "rgb(255,255,255)",
      "textHoverBg": "rgb(255,255,255)",
      "defaultColor": "rgb(0,0,145)",
      "defaultBorderColor": "rgb(0,0,145)",
      "defaultHoverColor": "rgb(0,0,145)",
      "defaultHoverBorderColor": "rgb(0,0,145)",
      "defaultHoverBg": "rgb(238,238,238)",
      "defaultActiveColor": "rgb(0,0,145)",
      "defaultActiveBorderColor": "rgb(0,0,145)",
      "colorPrimaryBgHover": "rgb(18,18,255)",
      "colorTextLightSolid": "rgb(255,255,255)",
      "colorError": "rgb(201,25,30)",
      "colorErrorActive": "rgb(249,90,92)",
      "colorErrorHover": "rgb(249,63,66)",
      "primaryShadow": "",
      "algorithm": true
    },
    "Tag": {
      "colorSuccessText": "#ffffff",
      "borderRadiusSM": 5,
      "algorithm": true
    },
    "Typography": {
      "fontFamilyCode": "'Marianne','SFMono-Regular', Consolas, 'Liberation Mono', Menlo, Courier, monospace",
      "colorText": "rgb(58,58,58)",
      "algorithm": true,
      "fontSize": 16,
      "fontSizeHeading1": 40,
      "fontSizeHeading2": 32,
      "fontSizeHeading3": 28,
      "fontSizeHeading4": 24,
      "fontSizeHeading5": 22
    },
    "InputNumber": {
      "activeBg": "rgb(238,238,238)",
      "activeBorderColor": "rgb(0,0,145)",
      "addonBg": "rgb(238,238,238)",
      "handleBorderColor": "rgb(238,238,238)",
      "handleHoverColor": "rgb(0,0,145)",
      "hoverBorderColor": "rgb(0,0,145)",
      "colorBgContainer": "rgb(238,238,238)",
      "borderRadius": 5,
      "borderRadiusLG": 5,
      "borderRadiusSM": 5,
      "hoverBg": "rgb(238,238,238)",
      "activeShadow": "",
      "errorActiveShadow": "",
      "warningActiveShadow": "",
      "motionDurationMid": "0s",
      "motionDurationSlow": "0s",
      "colorText": "rgb(58,58,58)"
    },
    "Select": {
      "motionDurationSlow": "0.s",
      "motionDurationMid": "0.s",
      "borderRadius": 5,
      "borderRadiusLG": 5,
      "borderRadiusSM": 5,
      "borderRadiusXS": 5,
      "activeBorderColor": "rgb(0,0,145)",
      "boxShadowSecondary": "",
      "activeOutlineColor": "rgb(255,255,255)",
      "hoverBorderColor": "rgb(0,0,145)",
      "optionSelectedBg": "rgb(238,238,238)",
      "colorBgBase": "rgb(238,238,238)"
    },
    "Dropdown": {
      "boxShadowPopoverArrow": "",
      "motionDurationMid": "0s",
      "boxShadowSecondary": "",
      "borderRadiusLG": 5,
      "borderRadiusSM": 5,
      "borderRadiusXS": 5
    },
    "Menu": {
      "motionDurationSlow": "0s",
      "motionDurationMid": "0s",
      "motionDurationFast": "0s",
      "boxShadowSecondary": "",
      "borderRadius": 5,
      "borderRadiusLG": 5,
      "itemBorderRadius": 5,
      "subMenuItemBorderRadius": 5,
      "itemHoverBg": "rgb(238,238,238)",
      "subMenuItemBg": "rgb(255,255,255)",
      "subMenuItemSelectedColor": "rgb(0,0,145)",
      "itemColor": "rgb(58,58,58)",
      "colorText": "rgb(58,58,58)",
      "horizontalItemSelectedBg": "rgb(227,227,253)",
      "horizontalItemSelectedColor": "rgb(0,0,145)"
    },
    "Slider": {
      "railSize": 8,
      "handleSize": 16,
      "borderRadiusXS": 20,
      "railBg": "rgb(255,255,255)",
      "railHoverBg": "rgb(255,255,255)",
      "trackBg": "rgb(0,0,145)",
      "colorPrimaryBorderHover": "rgb(0,0,145)",
      "handleActiveColor": "rgb(0,0,145)",
      "handleColor": "rgb(0,0,145)",
      "handleLineWidth": 1,
      "handleLineWidthHover": 1,
      "handleSizeHover": 16
    },
    "Pagination": {
      "borderRadius": 5,
      "borderRadiusLG": 5,
      "borderRadiusSM": 5,
      "itemInputBg": "rgb(238,238,238)",
      "colorBgContainer": "rgba(255,255,255,0)",
      "controlHeight": 32,
      "colorBgTextActive": "rgb(255,255,255)",
      "colorPrimaryBorder": "rgb(0,0,145)",
      "colorPrimaryHover": "rgb(0,0,145)",
      "colorBgTextHover": "rgb(241,241,241)",
      "itemSize": 32,
      "itemActiveColor": "rgb(255,255,255)",
      "itemBg": "rgb(255,255,255)",
      "itemActiveBg": "rgb(0,0,145)",
      "colorText": "rgb(102,102,102)"
    },
    "Input": {
      "borderRadius": 5,
      "borderRadiusLG": 5,
      "borderRadiusSM": 5,
      "activeBg": "rgb(238,238,238)",
      "activeBorderColor": "rgb(0,0,145)",
      "hoverBorderColor": "rgb(0,0,145)",
      "hoverBg": "rgb(238,238,238)",
      "addonBg": "rgb(238,238,238)",
      "colorText": "rgb(58,58,58)"
    },
    "Modal": {
      "borderRadiusLG": 5,
      "borderRadiusSM": 5,
      "colorText": "rgb(22,22,22)",
      "titleFontSize": 20,
      "colorIcon": "rgb(0,0,145)",
      "colorIconHover": "rgb(0,0,145)",
      "colorBgTextHover": "rgb(238,238,238)"
    },
    "Tooltip": {
      "borderRadius": 5,
      "borderRadiusXS": 5,
      "colorTextLightSolid": "rgb(58,58,58)",
      "colorBgSpotlight": "rgb(255,255,255)"
    },
    "Alert": {
      "borderRadiusLG": 5,
      "colorSuccessBg": "rgb(184,254,201)",
      "colorWarningBg": "rgb(255,233,230)",
      "colorErrorBg": "rgb(255,233,233)"
    },
    "Message": {
      "borderRadiusLG": 5
    },
    "Popover": {
      "borderRadiusLG": 5,
      "borderRadiusXS": 5,
      "fontWeightStrong": 800
    },
    "Checkbox": {
      "borderRadiusSM": 2,
      "controlInteractiveSize": 18,
      "colorPrimaryHover": "rgb(0,0,145)"
    },
    "Tabs": {
      "borderRadius": 5,
      "borderRadiusLG": 5,
      "inkBarColor": "rgb(0,0,145)",
      "itemActiveColor": "rgb(0,0,145)",
      "itemHoverColor": "rgba(58,58,58,0.88)",
      "cardBg": "rgb(227,227,253)"
    },
    "Table": {
      "headerBg": "rgb(246,246,246)",
      "borderRadius": 5,
      "headerBorderRadius": 5
    }
  }
}
```
