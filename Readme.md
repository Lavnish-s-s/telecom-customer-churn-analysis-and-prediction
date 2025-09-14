<!DOCTYPE html>
<!-- saved from url=(0055)https://markdownlivepreview.com/#churn-prediction-model -->
<html><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
    
    <meta http-equiv="content-language" content="en">
    <meta http-equiv="content-script-type" content="text/javascript">
    <meta http-equiv="content-style-type" content="text/css">
    <meta name="description" content="This is the online markdown editor with live preview.">

    <link rel="stylesheet" type="text/css" href="./Readme_files/style.css">
    <link rel="icon" type="image/png" href="https://markdownlivepreview.com/favicon.png">
    <title>Markdown Live Preview</title>
    <script type="module" crossorigin="" src="./Readme_files/index-DXVBtf7Z.js.download"></script>
    <link rel="stylesheet" crossorigin="" href="./Readme_files/index-C-vOJggO.css">
  <script async="" src="./Readme_files/js"></script><script>
    window.dataLayer = window.dataLayer || [];
    function gtag(){dataLayer.push(arguments);}
    gtag('js', new Date());

    gtag('config', 'G-77C1GEG9C8');
  </script><style type="text/css">.monaco-editor{font-family:-apple-system,BlinkMacSystemFont,"Segoe WPC","Segoe UI",HelveticaNeue-Light,system-ui,Ubuntu,"Droid Sans",sans-serif;--monaco-monospace-font:"SF Mono",Monaco,Menlo,Consolas,"Ubuntu Mono","Liberation Mono","DejaVu Sans Mono","Courier New",monospace}.monaco-menu .monaco-action-bar.vertical .action-item .action-menu-item:focus .action-label{stroke-width:1.2px}.monaco-editor.hc-black .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label,.monaco-editor.hc-light .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label,.monaco-editor.vs-dark .monaco-menu .monaco-action-bar.vertical .action-menu-item:focus .action-label{stroke-width:1.2px}.monaco-hover p{margin:0}.monaco-aria-container{position:absolute!important;top:0;height:1px;width:1px;margin:-1px;overflow:hidden;padding:0;clip:rect(1px,1px,1px,1px);clip-path:inset(50%)}.monaco-diff-editor .synthetic-focus,.monaco-diff-editor [tabindex="-1"]:focus,.monaco-diff-editor [tabindex="0"]:focus,.monaco-diff-editor button:focus,.monaco-diff-editor input[type=button]:focus,.monaco-diff-editor input[type=checkbox]:focus,.monaco-diff-editor input[type=search]:focus,.monaco-diff-editor input[type=text]:focus,.monaco-diff-editor select:focus,.monaco-diff-editor textarea:focus,.monaco-editor{outline-width:1px;outline-style:solid;outline-offset:-1px;outline-color:var(--vscode-focusBorder);opacity:1}</style><style type="text/css">.monaco-workbench .workbench-hover{position:relative;font-size:13px;line-height:19px;z-index:40;overflow:hidden;max-width:700px;background:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border);border-radius:3px;color:var(--vscode-editorHoverWidget-foreground);box-shadow:0 2px 8px var(--vscode-widget-shadow)}.monaco-workbench .workbench-hover hr{border-bottom:none}.monaco-workbench .workbench-hover:not(.skip-fade-in){animation:fadein .1s linear}.monaco-workbench .workbench-hover.compact{font-size:12px}.monaco-workbench .workbench-hover.compact .hover-contents{padding:2px 8px}.monaco-workbench .workbench-hover-container.locked .workbench-hover{outline:1px solid var(--vscode-editorHoverWidget-border)}.monaco-workbench .workbench-hover-container.locked .workbench-hover:focus,.monaco-workbench .workbench-hover-lock:focus{outline:1px solid var(--vscode-focusBorder)}.monaco-workbench .workbench-hover-container.locked .workbench-hover-lock:hover{background:var(--vscode-toolbar-hoverBackground)}.monaco-workbench .workbench-hover-pointer{position:absolute;z-index:41;pointer-events:none}.monaco-workbench .workbench-hover-pointer:after{content:'';position:absolute;width:5px;height:5px;background-color:var(--vscode-editorHoverWidget-background);border-right:1px solid var(--vscode-editorHoverWidget-border);border-bottom:1px solid var(--vscode-editorHoverWidget-border)}.monaco-workbench .locked .workbench-hover-pointer:after{width:4px;height:4px;border-right-width:2px;border-bottom-width:2px}.monaco-workbench .workbench-hover-pointer.left{left:-3px}.monaco-workbench .workbench-hover-pointer.right{right:3px}.monaco-workbench .workbench-hover-pointer.top{top:-3px}.monaco-workbench .workbench-hover-pointer.bottom{bottom:3px}.monaco-workbench .workbench-hover-pointer.left:after{transform:rotate(135deg)}.monaco-workbench .workbench-hover-pointer.right:after{transform:rotate(315deg)}.monaco-workbench .workbench-hover-pointer.top:after{transform:rotate(225deg)}.monaco-workbench .workbench-hover-pointer.bottom:after{transform:rotate(45deg)}.monaco-workbench .workbench-hover a{color:var(--vscode-textLink-foreground)}.monaco-workbench .workbench-hover a:focus{outline:1px solid;outline-offset:-1px;text-decoration:underline;outline-color:var(--vscode-focusBorder)}.monaco-workbench .workbench-hover a:active,.monaco-workbench .workbench-hover a:hover{color:var(--vscode-textLink-activeForeground)}.monaco-workbench .workbench-hover code{background:var(--vscode-textCodeBlock-background)}.monaco-workbench .workbench-hover .hover-row .actions{background:var(--vscode-editorHoverWidget-statusBarBackground)}.monaco-workbench .workbench-hover.right-aligned{left:1px}.monaco-workbench .workbench-hover.right-aligned .hover-row.status-bar .actions{flex-direction:row-reverse}.monaco-workbench .workbench-hover.right-aligned .hover-row.status-bar .actions .action-container{margin-right:0;margin-left:16px}</style><style type="text/css">.monaco-scrollable-element>.scrollbar>.scra{cursor:pointer;font-size:11px!important}.monaco-scrollable-element>.visible{opacity:1;background:rgba(0,0,0,0);transition:opacity .1s linear;z-index:11}.monaco-scrollable-element>.invisible{opacity:0;pointer-events:none}.monaco-scrollable-element>.invisible.fade{transition:opacity .8s linear}.monaco-scrollable-element>.shadow{position:absolute;display:none}.monaco-scrollable-element>.shadow.top{display:block;top:0;left:3px;height:3px;width:100%;box-shadow:var(--vscode-scrollbar-shadow) 0 6px 6px -6px inset}.monaco-scrollable-element>.shadow.left{display:block;top:3px;left:0;height:100%;width:3px;box-shadow:var(--vscode-scrollbar-shadow) 6px 0 6px -6px inset}.monaco-scrollable-element>.shadow.top-left-corner{display:block;top:0;left:0;height:3px;width:3px}.monaco-scrollable-element>.shadow.top.left{box-shadow:var(--vscode-scrollbar-shadow) 6px 0 6px -6px inset}.monaco-scrollable-element>.scrollbar>.slider{background:var(--vscode-scrollbarSlider-background)}.monaco-scrollable-element>.scrollbar>.slider:hover{background:var(--vscode-scrollbarSlider-hoverBackground)}.monaco-scrollable-element>.scrollbar>.slider.active{background:var(--vscode-scrollbarSlider-activeBackground)}</style><style type="text/css">.monaco-hover{cursor:default;position:absolute;overflow:hidden;user-select:text;-webkit-user-select:text;box-sizing:border-box;animation:fadein .1s linear;line-height:1.5em;white-space:var(--vscode-hover-whiteSpace,normal)}.monaco-hover.hidden{display:none}.monaco-hover a:hover:not(.disabled){cursor:pointer}.monaco-hover .hover-contents:not(.html-hover-contents){padding:4px 8px}.monaco-hover .markdown-hover>.hover-contents:not(.code-hover-contents){max-width:var(--vscode-hover-maxWidth,500px);word-wrap:break-word}.monaco-hover .markdown-hover>.hover-contents:not(.code-hover-contents) hr{min-width:100%}.monaco-hover .code,.monaco-hover h1,.monaco-hover h2,.monaco-hover h3,.monaco-hover h4,.monaco-hover h5,.monaco-hover h6,.monaco-hover p,.monaco-hover ul{margin:8px 0}.monaco-hover h1,.monaco-hover h2,.monaco-hover h3,.monaco-hover h4,.monaco-hover h5,.monaco-hover h6{line-height:1.1}.monaco-hover code{font-family:var(--monaco-monospace-font)}.monaco-hover hr{box-sizing:border-box;border-left:0;border-right:0px;margin-top:4px;margin-bottom:-4px;margin-left:-8px;margin-right:-8px;height:1px}.monaco-hover .code:first-child,.monaco-hover p:first-child,.monaco-hover ul:first-child{margin-top:0}.monaco-hover .code:last-child,.monaco-hover p:last-child,.monaco-hover ul:last-child{margin-bottom:0}.monaco-hover ul{padding-left:20px}.monaco-hover ol{padding-left:20px}.monaco-hover li>p{margin-bottom:0}.monaco-hover li>ul{margin-top:0}.monaco-hover code{border-radius:3px;padding:0 .4em}.monaco-hover .monaco-tokenized-source{white-space:var(--vscode-hover-sourceWhiteSpace,pre-wrap)}.monaco-hover .hover-row.status-bar{font-size:12px;line-height:22px}.monaco-hover .hover-row.status-bar .info{font-style:italic;padding:0 8px}.monaco-hover .hover-row.status-bar .actions{display:flex;padding:0 8px;width:100%}.monaco-hover .hover-row.status-bar .actions .action-container{margin-right:16px;cursor:pointer}.monaco-hover .hover-row.status-bar .actions .action-container .action .icon{padding-right:4px}.monaco-hover .hover-row.status-bar .actions .action-container a{color:var(--vscode-textLink-foreground);text-decoration:var(--text-link-decoration)}.monaco-hover .markdown-hover .hover-contents .codicon{color:inherit;font-size:inherit;vertical-align:middle}.monaco-hover .hover-contents a.code-link,.monaco-hover .hover-contents a.code-link:hover{color:inherit}.monaco-hover .hover-contents a.code-link:before{content:'('}.monaco-hover .hover-contents a.code-link:after{content:')'}.monaco-hover .hover-contents a.code-link>span{text-decoration:underline;border-bottom:1px solid transparent;text-underline-position:under;color:var(--vscode-textLink-foreground)}.monaco-hover .hover-contents a.code-link>span:hover{color:var(--vscode-textLink-activeForeground)}.monaco-hover .markdown-hover .hover-contents:not(.code-hover-contents):not(.html-hover-contents) span{margin-bottom:4px;display:inline-block}.monaco-hover .markdown-hover .hover-contents:not(.code-hover-contents):not(.html-hover-contents) span.codicon{margin-bottom:2px}.monaco-hover-content .action-container a{-webkit-user-select:none;user-select:none}.monaco-hover-content .action-container.disabled{pointer-events:none;opacity:.4;cursor:default}</style><style type="text/css">.monaco-editor .rendered-markdown kbd{background-color:var(--vscode-keybindingLabel-background);color:var(--vscode-keybindingLabel-foreground);border-style:solid;border-width:1px;border-radius:3px;border-color:var(--vscode-keybindingLabel-border);border-bottom-color:var(--vscode-keybindingLabel-bottomBorder);box-shadow:inset 0 -1px 0 var(--vscode-widget-shadow);vertical-align:middle;padding:1px 3px}.rendered-markdown li:has(input[type=checkbox]){list-style-type:none}</style><style type="text/css">.monaco-aria-container{position:absolute;left:-999em}</style><style type="text/css">.context-view{position:absolute}.context-view.fixed{all:initial;font-family:inherit;font-size:13px;position:fixed;color:inherit}</style><style type="text/css">.monaco-list{position:relative;height:100%;width:100%;white-space:nowrap}.monaco-list.mouse-support{user-select:none;-webkit-user-select:none}.monaco-list>.monaco-scrollable-element{height:100%}.monaco-list-rows{position:relative;width:100%;height:100%}.monaco-list.horizontal-scrolling .monaco-list-rows{width:auto;min-width:100%}.monaco-list-row{position:absolute;box-sizing:border-box;overflow:hidden;width:100%}.monaco-list.mouse-support .monaco-list-row{cursor:pointer;touch-action:none}.monaco-list .monaco-scrollable-element>.scrollbar.vertical,.monaco-pane-view>.monaco-split-view2.vertical>.monaco-scrollable-element>.scrollbar.vertical{z-index:14}.monaco-list-row.scrolling{display:none!important}.monaco-list.element-focused,.monaco-list.selection-multiple,.monaco-list.selection-single{outline:0!important}.monaco-drag-image{display:inline-block;padding:1px 7px;border-radius:10px;font-size:12px;position:absolute;z-index:1000}.monaco-list-type-filter-message{position:absolute;box-sizing:border-box;width:100%;height:100%;top:0;left:0;padding:40px 1em 1em 1em;text-align:center;white-space:normal;opacity:.7;pointer-events:none}.monaco-list-type-filter-message:empty{display:none}</style><style type="text/css">.monaco-select-box-dropdown-padding{--dropdown-padding-top:1px;--dropdown-padding-bottom:1px}.hc-black .monaco-select-box-dropdown-padding,.hc-light .monaco-select-box-dropdown-padding{--dropdown-padding-top:3px;--dropdown-padding-bottom:4px}.monaco-select-box-dropdown-container{display:none;box-sizing:border-box}.monaco-select-box-dropdown-container>.select-box-details-pane>.select-box-description-markdown *{margin:0}.monaco-select-box-dropdown-container>.select-box-details-pane>.select-box-description-markdown a:focus{outline:1px solid -webkit-focus-ring-color;outline-offset:-1px}.monaco-select-box-dropdown-container>.select-box-details-pane>.select-box-description-markdown code{line-height:15px;font-family:var(--monaco-monospace-font)}.monaco-select-box-dropdown-container.visible{display:flex;flex-direction:column;text-align:left;width:1px;overflow:hidden;border-bottom-left-radius:3px;border-bottom-right-radius:3px}.monaco-select-box-dropdown-container>.select-box-dropdown-list-container{flex:0 0 auto;align-self:flex-start;padding-top:var(--dropdown-padding-top);padding-bottom:var(--dropdown-padding-bottom);padding-left:1px;padding-right:1px;width:100%;overflow:hidden;box-sizing:border-box}.monaco-select-box-dropdown-container>.select-box-details-pane{padding:5px}.hc-black .monaco-select-box-dropdown-container>.select-box-dropdown-list-container{padding-top:var(--dropdown-padding-top);padding-bottom:var(--dropdown-padding-bottom)}.monaco-select-box-dropdown-container>.select-box-dropdown-list-container .monaco-list .monaco-list-row{cursor:pointer}.monaco-select-box-dropdown-container>.select-box-dropdown-list-container .monaco-list .monaco-list-row>.option-text{text-overflow:ellipsis;overflow:hidden;padding-left:3.5px;white-space:nowrap;float:left}.monaco-select-box-dropdown-container>.select-box-dropdown-list-container .monaco-list .monaco-list-row>.option-detail{text-overflow:ellipsis;overflow:hidden;padding-left:3.5px;white-space:nowrap;float:left;opacity:.7}.monaco-select-box-dropdown-container>.select-box-dropdown-list-container .monaco-list .monaco-list-row>.option-decorator-right{text-overflow:ellipsis;overflow:hidden;padding-right:10px;white-space:nowrap;float:right}.monaco-select-box-dropdown-container>.select-box-dropdown-list-container .monaco-list .monaco-list-row>.visually-hidden{position:absolute;left:-10000px;top:auto;width:1px;height:1px;overflow:hidden}.monaco-select-box-dropdown-container>.select-box-dropdown-container-width-control{flex:1 1 auto;align-self:flex-start;opacity:0}.monaco-select-box-dropdown-container>.select-box-dropdown-container-width-control>.width-control-div{overflow:hidden;max-height:0}.monaco-select-box-dropdown-container>.select-box-dropdown-container-width-control>.width-control-div>.option-text-width-control{padding-left:4px;padding-right:8px;white-space:nowrap}</style><style type="text/css">.monaco-select-box{width:100%;cursor:pointer;border-radius:2px}.monaco-select-box-dropdown-container{font-size:13px;font-weight:400;text-transform:none}.monaco-action-bar .action-item.select-container{cursor:default}.monaco-action-bar .action-item .monaco-select-box{cursor:pointer;min-width:100px;min-height:18px;padding:2px 23px 2px 8px}.mac .monaco-action-bar .action-item .monaco-select-box{font-size:11px;border-radius:5px}</style><style type="text/css">.monaco-action-bar{white-space:nowrap;height:100%}.monaco-action-bar .actions-container{display:flex;margin:0 auto;padding:0;height:100%;width:100%;align-items:center}.monaco-action-bar.vertical .actions-container{display:inline-block}.monaco-action-bar .action-item{display:block;align-items:center;justify-content:center;cursor:pointer;position:relative}.monaco-action-bar .action-item.disabled{cursor:default}.monaco-action-bar .action-item .codicon,.monaco-action-bar .action-item .icon{display:block}.monaco-action-bar .action-item .codicon{display:flex;align-items:center;width:16px;height:16px}.monaco-action-bar .action-label{display:flex;font-size:11px;padding:3px;border-radius:5px}.monaco-action-bar .action-item.disabled .action-label,.monaco-action-bar .action-item.disabled .action-label::before,.monaco-action-bar .action-item.disabled .action-label:hover{color:var(--vscode-disabledForeground)}.monaco-action-bar.vertical{text-align:left}.monaco-action-bar.vertical .action-item{display:block}.monaco-action-bar.vertical .action-label.separator{display:block;border-bottom:1px solid #bbb;padding-top:1px;margin-left:.8em;margin-right:.8em}.monaco-action-bar .action-item .action-label.separator{width:1px;height:16px;margin:5px 4px!important;cursor:default;min-width:1px;padding:0;background-color:#bbb}.secondary-actions .monaco-action-bar .action-label{margin-left:6px}.monaco-action-bar .action-item.select-container{overflow:hidden;flex:1;max-width:170px;min-width:60px;display:flex;align-items:center;justify-content:center;margin-right:10px}.monaco-action-bar .action-item.action-dropdown-item{display:flex}.monaco-action-bar .action-item.action-dropdown-item>.action-dropdown-item-separator{display:flex;align-items:center;cursor:default}.monaco-action-bar .action-item.action-dropdown-item>.action-dropdown-item-separator>div{width:1px}</style><style type="text/css">.monaco-dropdown{height:100%;padding:0}.monaco-dropdown>.dropdown-label{cursor:pointer;height:100%;display:flex;align-items:center;justify-content:center}.monaco-dropdown>.dropdown-label>.action-label.disabled{cursor:default}.monaco-dropdown-with-primary{display:flex!important;flex-direction:row;border-radius:5px}.monaco-dropdown-with-primary>.action-container>.action-label{margin-right:0}.monaco-dropdown-with-primary>.dropdown-action-container>.monaco-dropdown>.dropdown-label .codicon[class*=codicon-]{font-size:12px;padding-left:0;padding-right:0;line-height:16px;margin-left:-3px}.monaco-dropdown-with-primary>.dropdown-action-container>.monaco-dropdown>.dropdown-label>.action-label{display:block;background-size:16px;background-position:center center;background-repeat:no-repeat}</style><style type="text/css">.monaco-action-bar .action-item.menu-entry .action-label.icon{width:16px;height:16px;background-repeat:no-repeat;background-position:50%;background-size:16px}.monaco-action-bar .action-item.menu-entry.text-only .action-label{color:var(--vscode-descriptionForeground);overflow:hidden;border-radius:2px}.monaco-action-bar .action-item.menu-entry.text-only.use-comma:not(:last-of-type) .action-label::after{content:', '}.monaco-action-bar .action-item.menu-entry.text-only+.action-item:not(.text-only)>.monaco-dropdown .action-label{color:var(--vscode-descriptionForeground)}.monaco-dropdown-with-default{display:flex!important;flex-direction:row;border-radius:5px}.monaco-dropdown-with-default>.action-container>.action-label{margin-right:0}.monaco-dropdown-with-default>.action-container.menu-entry>.action-label.icon{width:16px;height:16px;background-repeat:no-repeat;background-position:50%;background-size:16px}.monaco-dropdown-with-default:hover{background-color:var(--vscode-toolbar-hoverBackground)}.monaco-dropdown-with-default>.dropdown-action-container>.monaco-dropdown>.dropdown-label .codicon[class*=codicon-]{font-size:12px;padding-left:0;padding-right:0;line-height:16px;margin-left:-3px}.monaco-dropdown-with-default>.dropdown-action-container>.monaco-dropdown>.dropdown-label>.action-label{display:block;background-size:16px;background-position:center center;background-repeat:no-repeat}</style><style type="text/css">.quick-input-widget{font-size:13px}.quick-input-widget .monaco-highlighted-label .highlight{color:#0066bf}.vs .quick-input-widget .monaco-list-row.focused .monaco-highlighted-label .highlight{color:#9dddff}.vs-dark .quick-input-widget .monaco-highlighted-label .highlight{color:#0097fb}.hc-black .quick-input-widget .monaco-highlighted-label .highlight{color:#f38518}.hc-light .quick-input-widget .monaco-highlighted-label .highlight{color:#0f4a85}.monaco-keybinding>.monaco-keybinding-key{background-color:rgba(221,221,221,.4);border:solid 1px rgba(204,204,204,.4);border-bottom-color:rgba(187,187,187,.4);box-shadow:inset 0 -1px 0 rgba(187,187,187,.4);color:#555}.hc-black .monaco-keybinding>.monaco-keybinding-key{background-color:transparent;border:solid 1px #6fc3df;box-shadow:none;color:#fff}.hc-light .monaco-keybinding>.monaco-keybinding-key{background-color:transparent;border:solid 1px #0f4a85;box-shadow:none;color:#292929}.vs-dark .monaco-keybinding>.monaco-keybinding-key{background-color:rgba(128,128,128,.17);border:solid 1px rgba(51,51,51,.6);border-bottom-color:rgba(68,68,68,.6);box-shadow:inset 0 -1px 0 rgba(68,68,68,.6);color:#ccc}</style><style type="text/css">.monaco-custom-toggle{margin-left:2px;float:left;cursor:pointer;overflow:hidden;width:20px;height:20px;border-radius:3px;border:1px solid transparent;padding:1px;box-sizing:border-box;user-select:none;-webkit-user-select:none}.monaco-custom-toggle:hover{background-color:var(--vscode-inputOption-hoverBackground)}.hc-black .monaco-custom-toggle:hover,.hc-light .monaco-custom-toggle:hover{border:1px dashed var(--vscode-focusBorder)}.hc-black .monaco-custom-toggle,.hc-light .monaco-custom-toggle{background:0 0}.hc-black .monaco-custom-toggle:hover,.hc-light .monaco-custom-toggle:hover{background:0 0}.monaco-custom-toggle.monaco-checkbox{height:18px;width:18px;border:1px solid transparent;border-radius:3px;margin-right:9px;margin-left:0;padding:0;opacity:1;background-size:16px!important}.monaco-action-bar .checkbox-action-item{display:flex;align-items:center;border-radius:2px;padding-right:2px}.monaco-action-bar .checkbox-action-item:hover{background-color:var(--vscode-toolbar-hoverBackground)}.monaco-action-bar .checkbox-action-item>.monaco-custom-toggle.monaco-checkbox{margin-right:4px}.monaco-action-bar .checkbox-action-item>.checkbox-label{font-size:12px}.monaco-custom-toggle.monaco-checkbox:not(.checked)::before{visibility:hidden}</style><style type="text/css">.quick-input-widget{position:absolute;width:600px;z-index:2550;left:50%;margin-left:-300px;-webkit-app-region:no-drag;border-radius:6px}.quick-input-titlebar{display:flex;align-items:center;border-top-right-radius:5px;border-top-left-radius:5px}.quick-input-left-action-bar{display:flex;margin-left:4px;flex:1}.quick-input-inline-action-bar{margin:2px 0 0 5px}.quick-input-title{padding:3px 0;text-align:center;text-overflow:ellipsis;overflow:hidden}.quick-input-right-action-bar{display:flex;margin-right:4px;flex:1}.quick-input-right-action-bar>.actions-container{justify-content:flex-end}.quick-input-titlebar .monaco-action-bar .action-label.codicon{background-position:center;background-repeat:no-repeat;padding:2px}.quick-input-description{margin:6px 6px 6px 11px}.quick-input-header .quick-input-description{margin:4px 2px;flex:1}.quick-input-header{display:flex;padding:8px 6px 2px 6px}.quick-input-widget.hidden-input .quick-input-header{padding:0;margin-bottom:0}.quick-input-and-message{display:flex;flex-direction:column;flex-grow:1;min-width:0;position:relative}.quick-input-check-all{align-self:center;margin:0}.quick-input-filter{flex-grow:1;display:flex;position:relative}.quick-input-box{flex-grow:1}.quick-input-widget.show-checkboxes .quick-input-box,.quick-input-widget.show-checkboxes .quick-input-message{margin-left:5px}.quick-input-visible-count{position:absolute;left:-10000px}.quick-input-count{align-self:center;position:absolute;right:4px;display:flex;align-items:center}.quick-input-count .monaco-count-badge{vertical-align:middle;padding:2px 4px;border-radius:2px;min-height:auto;line-height:normal}.quick-input-action{margin-left:6px}.quick-input-action .monaco-text-button{font-size:11px;padding:0 6px;display:flex;height:25px;align-items:center}.quick-input-message{margin-top:-1px;padding:5px;overflow-wrap:break-word}.quick-input-message>.codicon{margin:0 .2em;vertical-align:text-bottom}.quick-input-message a{color:inherit}.quick-input-progress.monaco-progress-container{position:relative}.quick-input-list{line-height:22px}.quick-input-widget.hidden-input .quick-input-list{margin-top:4px;padding-bottom:4px}.quick-input-list .monaco-list{overflow:hidden;max-height:calc(20 * 22px);padding-bottom:5px}.quick-input-list .monaco-scrollable-element{padding:0 5px}.quick-input-list .quick-input-list-entry{box-sizing:border-box;overflow:hidden;display:flex;padding:0 6px}.quick-input-list .quick-input-list-entry.quick-input-list-separator-border{border-top-width:1px;border-top-style:solid}.quick-input-list .monaco-list-row{border-radius:3px}.quick-input-list .monaco-list-row[data-index="0"] .quick-input-list-entry.quick-input-list-separator-border{border-top-style:none}.quick-input-list .quick-input-list-label{overflow:hidden;display:flex;height:100%;flex:1}.quick-input-list .quick-input-list-checkbox{align-self:center;margin:0}.quick-input-list .quick-input-list-icon{background-size:16px;background-position:left center;background-repeat:no-repeat;padding-right:6px;width:16px;height:22px;display:flex;align-items:center;justify-content:center}.quick-input-list .quick-input-list-rows{overflow:hidden;text-overflow:ellipsis;display:flex;flex-direction:column;height:100%;flex:1;margin-left:5px}.quick-input-widget.show-checkboxes .quick-input-list .quick-input-list-rows{margin-left:10px}.quick-input-widget .quick-input-list .quick-input-list-checkbox{display:none}.quick-input-widget.show-checkboxes .quick-input-list .quick-input-list-checkbox{display:inline}.quick-input-list .quick-input-list-rows>.quick-input-list-row{display:flex;align-items:center}.quick-input-list .quick-input-list-rows>.quick-input-list-row .monaco-icon-label,.quick-input-list .quick-input-list-rows>.quick-input-list-row .monaco-icon-label .monaco-icon-label-container>.monaco-icon-name-container{flex:1}.quick-input-list .quick-input-list-rows>.quick-input-list-row .codicon[class*=codicon-]{vertical-align:text-bottom}.quick-input-list .quick-input-list-rows .monaco-highlighted-label>span{opacity:1}.quick-input-list .quick-input-list-entry .quick-input-list-entry-keybinding{margin-right:8px}.quick-input-list .quick-input-list-label-meta{opacity:.7;line-height:normal;text-overflow:ellipsis;overflow:hidden}.quick-input-list .monaco-list .monaco-list-row .monaco-highlighted-label .highlight{font-weight:700;background-color:unset;color:var(--vscode-list-highlightForeground)!important}.quick-input-list .monaco-list .monaco-list-row.focused .monaco-highlighted-label .highlight{color:var(--vscode-list-focusHighlightForeground)!important}.quick-input-list .quick-input-list-entry .quick-input-list-separator{margin-right:4px}.quick-input-list .quick-input-list-entry-action-bar{display:flex;flex:0;overflow:visible}.quick-input-list .quick-input-list-entry-action-bar .action-label{display:none}.quick-input-list .quick-input-list-entry-action-bar .action-label.codicon{margin-right:4px;padding:2px}.quick-input-list .quick-input-list-entry-action-bar{margin-top:1px}.quick-input-list .quick-input-list-entry-action-bar{margin-right:4px}.quick-input-list .monaco-list-row.focused .quick-input-list-entry-action-bar .action-label,.quick-input-list .monaco-list-row.passive-focused .quick-input-list-entry-action-bar .action-label,.quick-input-list .quick-input-list-entry .quick-input-list-entry-action-bar .action-label.always-visible,.quick-input-list .quick-input-list-entry.focus-inside .quick-input-list-entry-action-bar .action-label,.quick-input-list .quick-input-list-entry:hover .quick-input-list-entry-action-bar .action-label{display:flex}.quick-input-list .monaco-list-row.focused .monaco-keybinding-key,.quick-input-list .monaco-list-row.focused .quick-input-list-entry .quick-input-list-separator{color:inherit}.quick-input-list .monaco-list-row.focused .monaco-keybinding-key{background:0 0}.quick-input-list .quick-input-list-separator-as-item{padding:4px 6px;font-size:12px}.quick-input-list .quick-input-list-separator-as-item .label-name{font-weight:600}.quick-input-list .quick-input-list-separator-as-item .label-description{opacity:1!important}.quick-input-list .monaco-tree-sticky-row .quick-input-list-entry.quick-input-list-separator-as-item.quick-input-list-separator-border{border-top-style:none}.quick-input-list .monaco-tree-sticky-row{padding:0 5px}.quick-input-list .monaco-tl-twistie{display:none!important}</style><style type="text/css">.monaco-text-button{box-sizing:border-box;display:flex;width:100%;padding:4px;border-radius:2px;text-align:center;cursor:pointer;justify-content:center;align-items:center;border:1px solid var(--vscode-button-border,transparent);line-height:18px}.monaco-text-button:focus{outline-offset:2px!important}.monaco-text-button:hover{text-decoration:none!important}.monaco-button.disabled,.monaco-button.disabled:focus{opacity:.4!important;cursor:default}.monaco-text-button .codicon{margin:0 .2em;color:inherit!important}.monaco-text-button.monaco-text-button-with-short-label{flex-direction:row;flex-wrap:wrap;padding:0 4px;overflow:hidden;height:28px}.monaco-text-button.monaco-text-button-with-short-label>.monaco-button-label{flex-basis:100%}.monaco-text-button.monaco-text-button-with-short-label>.monaco-button-label-short{flex-grow:1;width:0;overflow:hidden}.monaco-text-button.monaco-text-button-with-short-label>.monaco-button-label,.monaco-text-button.monaco-text-button-with-short-label>.monaco-button-label-short{display:flex;justify-content:center;align-items:center;font-weight:400;font-style:inherit;padding:4px 0}.monaco-button-dropdown{display:flex;cursor:pointer}.monaco-button-dropdown.disabled{cursor:default}.monaco-button-dropdown>.monaco-button:focus{outline-offset:-1px!important}.monaco-button-dropdown.disabled>.monaco-button-dropdown-separator,.monaco-button-dropdown.disabled>.monaco-button.disabled,.monaco-button-dropdown.disabled>.monaco-button.disabled:focus{opacity:.4!important}.monaco-button-dropdown>.monaco-button.monaco-text-button{border-right-width:0!important}.monaco-button-dropdown .monaco-button-dropdown-separator{padding:4px 0;cursor:default}.monaco-button-dropdown .monaco-button-dropdown-separator>div{height:100%;width:1px}.monaco-button-dropdown>.monaco-button.monaco-dropdown-button{border:1px solid var(--vscode-button-border,transparent);border-left-width:0!important;border-radius:0 2px 2px 0;display:flex;align-items:center}.monaco-button-dropdown>.monaco-button.monaco-text-button{border-radius:2px 0 0 2px}.monaco-description-button{display:flex;flex-direction:column;align-items:center;margin:4px 5px}.monaco-description-button .monaco-button-description{font-style:italic;font-size:11px;padding:4px 20px}.monaco-description-button .monaco-button-description,.monaco-description-button .monaco-button-label{display:flex;justify-content:center;align-items:center}.monaco-description-button .monaco-button-description>.codicon,.monaco-description-button .monaco-button-label>.codicon{margin:0 .2em;color:inherit!important}.monaco-button-dropdown.default-colors>.monaco-button,.monaco-button.default-colors{color:var(--vscode-button-foreground);background-color:var(--vscode-button-background)}.monaco-button-dropdown.default-colors>.monaco-button:hover,.monaco-button.default-colors:hover{background-color:var(--vscode-button-hoverBackground)}.monaco-button-dropdown.default-colors>.monaco-button.secondary,.monaco-button.default-colors.secondary{color:var(--vscode-button-secondaryForeground);background-color:var(--vscode-button-secondaryBackground)}.monaco-button-dropdown.default-colors>.monaco-button.secondary:hover,.monaco-button.default-colors.secondary:hover{background-color:var(--vscode-button-secondaryHoverBackground)}.monaco-button-dropdown.default-colors .monaco-button-dropdown-separator{background-color:var(--vscode-button-background);border-top:1px solid var(--vscode-button-border);border-bottom:1px solid var(--vscode-button-border)}.monaco-button-dropdown.default-colors .monaco-button.secondary+.monaco-button-dropdown-separator{background-color:var(--vscode-button-secondaryBackground)}.monaco-button-dropdown.default-colors .monaco-button-dropdown-separator>div{background-color:var(--vscode-button-separator)}</style><style type="text/css">.monaco-count-badge{padding:3px 6px;border-radius:11px;font-size:11px;min-width:18px;min-height:18px;line-height:11px;font-weight:400;text-align:center;display:inline-block;box-sizing:border-box}.monaco-count-badge.long{padding:2px 3px;border-radius:2px;min-height:auto;line-height:normal}</style><style type="text/css">.monaco-progress-container{width:100%;height:2px;overflow:hidden}.monaco-progress-container .progress-bit{width:2%;height:2px;position:absolute;left:0;display:none}.monaco-progress-container.active .progress-bit{display:inherit}.monaco-progress-container.discrete .progress-bit{left:0;transition:width .1s linear}.monaco-progress-container.discrete.done .progress-bit{width:100%}.monaco-progress-container.infinite .progress-bit{animation-name:progress;animation-duration:4s;animation-iteration-count:infinite;transform:translate3d(0,0,0);animation-timing-function:linear}.monaco-progress-container.infinite.infinite-long-running .progress-bit{animation-timing-function:steps(100)}@keyframes progress{from{transform:translateX(0) scaleX(1)}50%{transform:translateX(2500%) scaleX(3)}to{transform:translateX(4900%) scaleX(1)}}</style><style type="text/css">.monaco-inputbox{position:relative;display:block;padding:0;box-sizing:border-box;border-radius:2px;font-size:inherit}.monaco-inputbox>.ibwrapper>.input,.monaco-inputbox>.ibwrapper>.mirror{padding:4px 6px}.monaco-inputbox>.ibwrapper{position:relative;width:100%;height:100%}.monaco-inputbox>.ibwrapper>.input{display:inline-block;box-sizing:border-box;width:100%;height:100%;line-height:inherit;border:none;font-family:inherit;font-size:inherit;resize:none;color:inherit}.monaco-inputbox>.ibwrapper>input{text-overflow:ellipsis}.monaco-inputbox>.ibwrapper>textarea.input{display:block;scrollbar-width:none;outline:0}.monaco-inputbox>.ibwrapper>textarea.input::-webkit-scrollbar{display:none}.monaco-inputbox>.ibwrapper>textarea.input.empty{white-space:nowrap}.monaco-inputbox>.ibwrapper>.mirror{position:absolute;display:inline-block;width:100%;top:0;left:0;box-sizing:border-box;white-space:pre-wrap;visibility:hidden;word-wrap:break-word}.monaco-inputbox-container{text-align:right}.monaco-inputbox-container .monaco-inputbox-message{display:inline-block;overflow:hidden;text-align:left;width:100%;box-sizing:border-box;padding:.4em;font-size:12px;line-height:17px;margin-top:-1px;word-wrap:break-word}.monaco-inputbox .monaco-action-bar{position:absolute;right:2px;top:4px}.monaco-inputbox .monaco-action-bar .action-item{margin-left:2px}.monaco-inputbox .monaco-action-bar .action-item .codicon{background-repeat:no-repeat;width:16px;height:16px}</style><style type="text/css">.monaco-findInput{position:relative}.monaco-findInput .monaco-inputbox{font-size:13px;width:100%}.monaco-findInput>.controls{position:absolute;top:3px;right:2px}.vs .monaco-findInput.disabled{background-color:#e1e1e1}.vs-dark .monaco-findInput.disabled{background-color:#333}.hc-light .monaco-findInput.highlight-0 .controls,.monaco-findInput.highlight-0 .controls{animation:monaco-findInput-highlight-0 .1s linear 0s}.hc-light .monaco-findInput.highlight-1 .controls,.monaco-findInput.highlight-1 .controls{animation:monaco-findInput-highlight-1 .1s linear 0s}.hc-black .monaco-findInput.highlight-0 .controls,.vs-dark .monaco-findInput.highlight-0 .controls{animation:monaco-findInput-highlight-dark-0 .1s linear 0s}.hc-black .monaco-findInput.highlight-1 .controls,.vs-dark .monaco-findInput.highlight-1 .controls{animation:monaco-findInput-highlight-dark-1 .1s linear 0s}@keyframes monaco-findInput-highlight-0{0%{background:rgba(253,255,0,.8)}100%{background:0 0}}@keyframes monaco-findInput-highlight-1{0%{background:rgba(253,255,0,.8)}99%{background:0 0}}@keyframes monaco-findInput-highlight-dark-0{0%{background:rgba(255,255,255,.44)}100%{background:0 0}}@keyframes monaco-findInput-highlight-dark-1{0%{background:rgba(255,255,255,.44)}99%{background:0 0}}</style><style type="text/css">:root{--vscode-sash-size:4px;--vscode-sash-hover-size:4px}.monaco-sash{position:absolute;z-index:35;touch-action:none}.monaco-sash.disabled{pointer-events:none}.monaco-sash.mac.vertical{cursor:col-resize}.monaco-sash.vertical.minimum{cursor:e-resize}.monaco-sash.vertical.maximum{cursor:w-resize}.monaco-sash.mac.horizontal{cursor:row-resize}.monaco-sash.horizontal.minimum{cursor:s-resize}.monaco-sash.horizontal.maximum{cursor:n-resize}.monaco-sash.disabled{cursor:default!important;pointer-events:none!important}.monaco-sash.vertical{cursor:ew-resize;top:0;width:var(--vscode-sash-size);height:100%}.monaco-sash.horizontal{cursor:ns-resize;left:0;width:100%;height:var(--vscode-sash-size)}.monaco-sash:not(.disabled)>.orthogonal-drag-handle{content:" ";height:calc(var(--vscode-sash-size) * 2);width:calc(var(--vscode-sash-size) * 2);z-index:100;display:block;cursor:all-scroll;position:absolute}.monaco-sash.horizontal.orthogonal-edge-north:not(.disabled)>.orthogonal-drag-handle.start,.monaco-sash.horizontal.orthogonal-edge-south:not(.disabled)>.orthogonal-drag-handle.end{cursor:nwse-resize}.monaco-sash.horizontal.orthogonal-edge-north:not(.disabled)>.orthogonal-drag-handle.end,.monaco-sash.horizontal.orthogonal-edge-south:not(.disabled)>.orthogonal-drag-handle.start{cursor:nesw-resize}.monaco-sash.vertical>.orthogonal-drag-handle.start{left:calc(var(--vscode-sash-size) * -.5);top:calc(var(--vscode-sash-size) * -1)}.monaco-sash.vertical>.orthogonal-drag-handle.end{left:calc(var(--vscode-sash-size) * -.5);bottom:calc(var(--vscode-sash-size) * -1)}.monaco-sash.horizontal>.orthogonal-drag-handle.start{top:calc(var(--vscode-sash-size) * -.5);left:calc(var(--vscode-sash-size) * -1)}.monaco-sash.horizontal>.orthogonal-drag-handle.end{top:calc(var(--vscode-sash-size) * -.5);right:calc(var(--vscode-sash-size) * -1)}.monaco-sash:before{content:'';pointer-events:none;position:absolute;width:100%;height:100%;background:0 0}.monaco-workbench:not(.reduce-motion) .monaco-sash:before{transition:background-color .1s ease-out}.monaco-sash.active:before,.monaco-sash.hover:before{background:var(--vscode-sash-hoverBorder)}.monaco-sash.vertical:before{width:var(--vscode-sash-hover-size);left:calc(50% - (var(--vscode-sash-hover-size)/ 2))}.monaco-sash.horizontal:before{height:var(--vscode-sash-hover-size);top:calc(50% - (var(--vscode-sash-hover-size)/ 2))}.pointer-events-disabled{pointer-events:none!important}.monaco-sash.debug{background:#0ff}.monaco-sash.debug.disabled{background:rgba(0,255,255,.2)}.monaco-sash.debug:not(.disabled)>.orthogonal-drag-handle{background:red}</style><style type="text/css">.monaco-split-view2{position:relative;width:100%;height:100%}.monaco-split-view2>.sash-container{position:absolute;width:100%;height:100%;pointer-events:none}.monaco-split-view2>.sash-container>.monaco-sash{pointer-events:initial}.monaco-split-view2>.monaco-scrollable-element{width:100%;height:100%}.monaco-split-view2>.monaco-scrollable-element>.split-view-container{width:100%;height:100%;white-space:nowrap;position:relative}.monaco-split-view2>.monaco-scrollable-element>.split-view-container>.split-view-view{white-space:initial;position:absolute}.monaco-split-view2>.monaco-scrollable-element>.split-view-container>.split-view-view:not(.visible){display:none}.monaco-split-view2.vertical>.monaco-scrollable-element>.split-view-container>.split-view-view{width:100%}.monaco-split-view2.horizontal>.monaco-scrollable-element>.split-view-container>.split-view-view{height:100%}.monaco-split-view2.separator-border>.monaco-scrollable-element>.split-view-container>.split-view-view:not(:first-child)::before{content:' ';position:absolute;top:0;left:0;z-index:5;pointer-events:none;background-color:var(--separator-border)}.monaco-split-view2.separator-border.horizontal>.monaco-scrollable-element>.split-view-container>.split-view-view:not(:first-child)::before{height:100%;width:1px}.monaco-split-view2.separator-border.vertical>.monaco-scrollable-element>.split-view-container>.split-view-view:not(:first-child)::before{height:1px;width:100%}</style><style type="text/css">.monaco-table{display:flex;flex-direction:column;position:relative;height:100%;width:100%;white-space:nowrap;overflow:hidden}.monaco-table>.monaco-split-view2{border-bottom:1px solid transparent}.monaco-table>.monaco-list{flex:1}.monaco-table-tr{display:flex;height:100%}.monaco-table-th{width:100%;height:100%;font-weight:700;overflow:hidden;text-overflow:ellipsis}.monaco-table-td,.monaco-table-th{box-sizing:border-box;flex-shrink:0;overflow:hidden;white-space:nowrap;text-overflow:ellipsis}.monaco-table>.monaco-split-view2 .monaco-sash.vertical::before{content:"";position:absolute;left:calc(var(--vscode-sash-size)/ 2);width:0;border-left:1px solid transparent}.monaco-workbench:not(.reduce-motion) .monaco-table>.monaco-split-view2,.monaco-workbench:not(.reduce-motion) .monaco-table>.monaco-split-view2 .monaco-sash.vertical::before{transition:border-color .2s ease-out}</style><style type="text/css">.monaco-tl-row{display:flex;height:100%;align-items:center;position:relative}.monaco-tl-row.disabled{cursor:default}.monaco-tl-indent{height:100%;position:absolute;top:0;left:16px;pointer-events:none}.hide-arrows .monaco-tl-indent{left:12px}.monaco-tl-indent>.indent-guide{display:inline-block;box-sizing:border-box;height:100%;border-left:1px solid transparent}.monaco-workbench:not(.reduce-motion) .monaco-tl-indent>.indent-guide{transition:border-color .1s linear}.monaco-tl-contents,.monaco-tl-twistie{height:100%}.monaco-tl-twistie{font-size:10px;text-align:right;padding-right:6px;flex-shrink:0;width:16px;display:flex!important;align-items:center;justify-content:center;transform:translateX(3px)}.monaco-tl-contents{flex:1;overflow:hidden}.monaco-tl-twistie::before{border-radius:20px}.monaco-tl-twistie.collapsed::before{transform:rotate(-90deg)}.monaco-tl-twistie.codicon-tree-item-loading::before{animation:codicon-spin 1.25s steps(30) infinite}.monaco-tree-type-filter{position:absolute;top:0;display:flex;padding:3px;max-width:200px;z-index:100;margin:0 6px;border:1px solid var(--vscode-widget-border);border-bottom-left-radius:4px;border-bottom-right-radius:4px}.monaco-workbench:not(.reduce-motion) .monaco-tree-type-filter{transition:top .3s}.monaco-tree-type-filter.disabled{top:-40px!important}.monaco-tree-type-filter-grab{display:flex!important;align-items:center;justify-content:center;cursor:grab;margin-right:2px}.monaco-tree-type-filter-grab.grabbing{cursor:grabbing}.monaco-tree-type-filter-input{flex:1}.monaco-tree-type-filter-input .monaco-inputbox{height:23px}.monaco-tree-type-filter-input .monaco-inputbox>.ibwrapper>.input,.monaco-tree-type-filter-input .monaco-inputbox>.ibwrapper>.mirror{padding:2px 4px}.monaco-tree-type-filter-input .monaco-findInput>.controls{top:2px}.monaco-tree-type-filter-actionbar{margin-left:4px}.monaco-tree-type-filter-actionbar .monaco-action-bar .action-label{padding:2px}.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container{position:absolute;top:0;left:0;width:100%;height:0;z-index:13;background-color:var(--vscode-sideBar-background)}.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container .monaco-tree-sticky-row.monaco-list-row{position:absolute;width:100%;opacity:1!important;overflow:hidden;background-color:var(--vscode-sideBar-background)}.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container .monaco-tree-sticky-row:hover{background-color:var(--vscode-list-hoverBackground)!important;cursor:pointer}.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container.empty,.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container.empty .monaco-tree-sticky-container-shadow{display:none}.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container .monaco-tree-sticky-container-shadow{position:absolute;bottom:-3px;left:0;height:0;width:100%}.monaco-list .monaco-scrollable-element .monaco-tree-sticky-container[tabindex="0"]:focus{outline:0}</style><style type="text/css">.monaco-icon-label{display:flex;overflow:hidden;text-overflow:ellipsis}.monaco-icon-label::before{background-size:16px;background-position:left center;background-repeat:no-repeat;padding-right:6px;width:16px;height:22px;line-height:inherit!important;display:inline-block;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;vertical-align:top;flex-shrink:0}.monaco-icon-label-iconpath{width:16px;height:16px;padding-left:2px;margin-top:2px;display:flex}.monaco-icon-label-container.disabled{color:var(--vscode-disabledForeground)}.monaco-icon-label>.monaco-icon-label-container{min-width:0;overflow:hidden;text-overflow:ellipsis;flex:1}.monaco-icon-label>.monaco-icon-label-container>.monaco-icon-name-container>.label-name{color:inherit;white-space:pre}.monaco-icon-label>.monaco-icon-label-container>.monaco-icon-name-container>.label-name>.label-separator{margin:0 2px;opacity:.5}.monaco-icon-label>.monaco-icon-label-container>.monaco-icon-suffix-container>.label-suffix{opacity:.7;white-space:pre}.monaco-icon-label>.monaco-icon-label-container>.monaco-icon-description-container>.label-description{opacity:.7;margin-left:.5em;font-size:.9em;white-space:pre}.monaco-icon-label.nowrap>.monaco-icon-label-container>.monaco-icon-description-container>.label-description{white-space:nowrap}.vs .monaco-icon-label>.monaco-icon-label-container>.monaco-icon-description-container>.label-description{opacity:.95}.monaco-icon-label.italic>.monaco-icon-label-container>.monaco-icon-description-container>.label-description,.monaco-icon-label.italic>.monaco-icon-label-container>.monaco-icon-name-container>.label-name{font-style:italic}.monaco-icon-label.deprecated{text-decoration:line-through;opacity:.66}.monaco-icon-label.italic::after{font-style:italic}.monaco-icon-label.strikethrough>.monaco-icon-label-container>.monaco-icon-description-container>.label-description,.monaco-icon-label.strikethrough>.monaco-icon-label-container>.monaco-icon-name-container>.label-name{text-decoration:line-through}.monaco-icon-label::after{opacity:.75;font-size:90%;font-weight:600;margin:auto 16px 0 5px;text-align:center}.monaco-list:focus .selected .monaco-icon-label,.monaco-list:focus .selected .monaco-icon-label::after{color:inherit!important}.monaco-list-row.focused.selected .label-description,.monaco-list-row.selected .label-description{opacity:.8}</style><style type="text/css">.monaco-keybinding{display:flex;align-items:center;line-height:10px}.monaco-keybinding>.monaco-keybinding-key{display:inline-block;border-style:solid;border-width:1px;border-radius:3px;vertical-align:middle;font-size:11px;padding:3px 5px;margin:0 2px}.monaco-keybinding>.monaco-keybinding-key:first-child{margin-left:0}.monaco-keybinding>.monaco-keybinding-key:last-child{margin-right:0}.monaco-keybinding>.monaco-keybinding-key-separator{display:inline-block}.monaco-keybinding>.monaco-keybinding-key-chord-separator{width:6px}</style><style type="text/css">::-ms-clear{display:none}.monaco-editor .editor-widget input{color:inherit}.monaco-editor{position:relative;overflow:visible;-webkit-text-size-adjust:100%;color:var(--vscode-editor-foreground);background-color:var(--vscode-editor-background);overflow-wrap:initial}.monaco-editor-background{background-color:var(--vscode-editor-background)}.monaco-editor .rangeHighlight{background-color:var(--vscode-editor-rangeHighlightBackground);box-sizing:border-box;border:1px solid var(--vscode-editor-rangeHighlightBorder)}.monaco-editor.hc-black .rangeHighlight,.monaco-editor.hc-light .rangeHighlight{border-style:dotted}.monaco-editor .symbolHighlight{background-color:var(--vscode-editor-symbolHighlightBackground);box-sizing:border-box;border:1px solid var(--vscode-editor-symbolHighlightBorder)}.monaco-editor.hc-black .symbolHighlight,.monaco-editor.hc-light .symbolHighlight{border-style:dotted}.monaco-editor .overflow-guard{position:relative;overflow:hidden}.monaco-editor .view-overlays{position:absolute;top:0}.monaco-editor .margin-view-overlays>div,.monaco-editor .view-overlays>div{position:absolute;width:100%}.monaco-editor .squiggly-error{border-bottom:4px double var(--vscode-editorError-border)}.monaco-editor .squiggly-error::before{display:block;content:'';width:100%;height:100%;background:var(--vscode-editorError-background)}.monaco-editor .squiggly-warning{border-bottom:4px double var(--vscode-editorWarning-border)}.monaco-editor .squiggly-warning::before{display:block;content:'';width:100%;height:100%;background:var(--vscode-editorWarning-background)}.monaco-editor .squiggly-info{border-bottom:4px double var(--vscode-editorInfo-border)}.monaco-editor .squiggly-info::before{display:block;content:'';width:100%;height:100%;background:var(--vscode-editorInfo-background)}.monaco-editor .squiggly-hint{border-bottom:2px dotted var(--vscode-editorHint-border)}.monaco-editor.showUnused .squiggly-unnecessary{border-bottom:2px dashed var(--vscode-editorUnnecessaryCode-border)}.monaco-editor.showDeprecated .squiggly-inline-deprecated{text-decoration:line-through;text-decoration-color:var(--vscode-editor-foreground,inherit)}</style><style type="text/css">.monaco-editor .inputarea{min-width:0;min-height:0;margin:0;padding:0;position:absolute;outline:0!important;resize:none;border:none;overflow:hidden;color:transparent;background-color:transparent;z-index:-10}.monaco-editor .inputarea.ime-input{z-index:10;caret-color:var(--vscode-editorCursor-foreground);color:var(--vscode-editor-foreground)}</style><style type="text/css">.monaco-editor .margin-view-overlays .line-numbers{bottom:0;font-variant-numeric:tabular-nums;position:absolute;text-align:right;display:inline-block;vertical-align:middle;box-sizing:border-box;cursor:default}.monaco-editor .relative-current-line-number{text-align:left;display:inline-block;width:100%}.monaco-editor .margin-view-overlays .line-numbers.lh-odd{margin-top:1px}.monaco-editor .line-numbers{color:var(--vscode-editorLineNumber-foreground)}.monaco-editor .line-numbers.active-line-number{color:var(--vscode-editorLineNumber-activeForeground)}</style><style type="text/css">.monaco-editor .margin{background-color:var(--vscode-editorGutter-background)}</style><style type="text/css">.monaco-mouse-cursor-text{cursor:text}</style><style type="text/css">.monaco-editor .blockDecorations-container{position:absolute;top:0;pointer-events:none}.monaco-editor .blockDecorations-block{position:absolute;box-sizing:border-box}</style><style type="text/css">.monaco-editor .view-overlays .current-line{display:block;position:absolute;left:0;top:0;box-sizing:border-box;height:100%}.monaco-editor .margin-view-overlays .current-line{display:block;position:absolute;left:0;top:0;box-sizing:border-box;height:100%}.monaco-editor .margin-view-overlays .current-line.current-line-margin.current-line-margin-both{border-right:0}</style><style type="text/css">.monaco-editor .lines-content .cdr{position:absolute;height:100%}</style><style type="text/css">.monaco-editor .glyph-margin{position:absolute;top:0}.monaco-editor .glyph-margin-widgets .cgmr{position:absolute;display:flex;align-items:center;justify-content:center}.monaco-editor .glyph-margin-widgets .cgmr.codicon-modifier-spin::before{position:absolute;top:50%;left:50%;transform:translate(-50%,-50%)}</style><style type="text/css">.monaco-editor .lines-content .core-guide{position:absolute;box-sizing:border-box;height:100%}</style><style type="text/css">.mtkcontrol{color:#fff!important;background:#960000!important}.mtkoverflow{background-color:var(--vscode-button-background,var(--vscode-editor-background));color:var(--vscode-button-foreground,var(--vscode-editor-foreground));border-width:1px;border-style:solid;border-color:var(--vscode-contrastBorder);border-radius:2px;padding:4px;cursor:pointer}.mtkoverflow:hover{background-color:var(--vscode-button-hoverBackground)}.monaco-editor.no-user-select .lines-content,.monaco-editor.no-user-select .view-line,.monaco-editor.no-user-select .view-lines{user-select:none;-webkit-user-select:none}.monaco-editor.mac .lines-content:hover,.monaco-editor.mac .view-line:hover,.monaco-editor.mac .view-lines:hover{user-select:text;-webkit-user-select:text;-ms-user-select:text}.monaco-editor.enable-user-select{user-select:initial;-webkit-user-select:initial}.monaco-editor .view-lines{white-space:nowrap}.monaco-editor .view-line{position:absolute;width:100%}.monaco-editor .lines-content>.view-lines>.view-line>span{top:0;bottom:0;position:absolute}.monaco-editor .mtkw{color:var(--vscode-editorWhitespace-foreground)!important}.monaco-editor .mtkz{display:inline-block;color:var(--vscode-editorWhitespace-foreground)!important}</style><style type="text/css">.monaco-editor .lines-decorations{position:absolute;top:0;background:#fff}.monaco-editor .margin-view-overlays .cldr{position:absolute;height:100%}</style><style type="text/css">.monaco-editor .margin-view-overlays .cmdr{position:absolute;left:0;width:100%;height:100%}</style><style type="text/css">.monaco-editor .minimap.slider-mouseover .minimap-slider{opacity:0;transition:opacity .1s linear}.monaco-editor .minimap.slider-mouseover:hover .minimap-slider{opacity:1}.monaco-editor .minimap.slider-mouseover .minimap-slider.active{opacity:1}.monaco-editor .minimap-slider .minimap-slider-horizontal{background:var(--vscode-minimapSlider-background)}.monaco-editor .minimap-slider:hover .minimap-slider-horizontal{background:var(--vscode-minimapSlider-hoverBackground)}.monaco-editor .minimap-slider.active .minimap-slider-horizontal{background:var(--vscode-minimapSlider-activeBackground)}.monaco-editor .minimap-shadow-visible{box-shadow:var(--vscode-scrollbar-shadow) -6px 0 6px -6px inset}.monaco-editor .minimap-shadow-hidden{position:absolute;width:0}.monaco-editor .minimap-shadow-visible{position:absolute;left:-6px;width:6px}.monaco-editor.no-minimap-shadow .minimap-shadow-visible{position:absolute;left:-1px;width:1px}.minimap.autohide{opacity:0;transition:opacity .5s}.minimap.autohide:hover{opacity:1}.monaco-editor .minimap{z-index:5}</style><style type="text/css">.monaco-editor .overlayWidgets{position:absolute;top:0;left:0}</style><style type="text/css">.monaco-editor .view-ruler{position:absolute;top:0;box-shadow:1px 0 0 0 var(--vscode-editorRuler-foreground) inset}</style><style type="text/css">.monaco-editor .scroll-decoration{position:absolute;top:0;left:0;height:6px;box-shadow:var(--vscode-scrollbar-shadow) 0 6px 6px -6px inset}</style><style type="text/css">.monaco-editor .lines-content .cslr{position:absolute}.monaco-editor .focused .selected-text{background-color:var(--vscode-editor-selectionBackground)}.monaco-editor .selected-text{background-color:var(--vscode-editor-inactiveSelectionBackground)}.monaco-editor .top-left-radius{border-top-left-radius:3px}.monaco-editor .bottom-left-radius{border-bottom-left-radius:3px}.monaco-editor .top-right-radius{border-top-right-radius:3px}.monaco-editor .bottom-right-radius{border-bottom-right-radius:3px}.monaco-editor.hc-black .top-left-radius{border-top-left-radius:0}.monaco-editor.hc-black .bottom-left-radius{border-bottom-left-radius:0}.monaco-editor.hc-black .top-right-radius{border-top-right-radius:0}.monaco-editor.hc-black .bottom-right-radius{border-bottom-right-radius:0}.monaco-editor.hc-light .top-left-radius{border-top-left-radius:0}.monaco-editor.hc-light .bottom-left-radius{border-bottom-left-radius:0}.monaco-editor.hc-light .top-right-radius{border-top-right-radius:0}.monaco-editor.hc-light .bottom-right-radius{border-bottom-right-radius:0}</style><style type="text/css">.monaco-editor .cursors-layer{position:absolute;top:0}.monaco-editor .cursors-layer>.cursor{position:absolute;overflow:hidden;box-sizing:border-box}.monaco-editor .cursors-layer.cursor-smooth-caret-animation>.cursor{transition:all 80ms}.monaco-editor .cursors-layer.cursor-block-outline-style>.cursor{background:0 0!important;border-style:solid;border-width:1px}.monaco-editor .cursors-layer.cursor-underline-style>.cursor{border-bottom-width:2px;border-bottom-style:solid;background:0 0!important}.monaco-editor .cursors-layer.cursor-underline-thin-style>.cursor{border-bottom-width:1px;border-bottom-style:solid;background:0 0!important}@keyframes monaco-cursor-smooth{0%,20%{opacity:1}100%,60%{opacity:0}}@keyframes monaco-cursor-phase{0%,20%{opacity:1}100%,90%{opacity:0}}@keyframes monaco-cursor-expand{0%,20%{transform:scaleY(1)}100%,80%{transform:scaleY(0)}}.cursor-smooth{animation:monaco-cursor-smooth .5s ease-in-out 0s 20 alternate}.cursor-phase{animation:monaco-cursor-phase .5s ease-in-out 0s 20 alternate}.cursor-expand>.cursor{animation:monaco-cursor-expand .5s ease-in-out 0s 20 alternate}</style><style type="text/css">.monaco-editor .mwh{position:absolute;color:var(--vscode-editorWhitespace-foreground)!important}</style><style type="text/css">/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor .diff-hidden-lines-widget {
	width: 100%;
}

.monaco-editor .diff-hidden-lines {
	height: 0px; /* The children each have a fixed height, the transform confuses the browser */
	transform: translate(0px, -10px);
	font-size: 13px;
	line-height: 14px;
}

.monaco-editor .diff-hidden-lines:not(.dragging) .top:hover,
.monaco-editor .diff-hidden-lines:not(.dragging) .bottom:hover,
.monaco-editor .diff-hidden-lines .top.dragging,
.monaco-editor .diff-hidden-lines .bottom.dragging {
	background-color: var(--vscode-focusBorder);
}

.monaco-editor .diff-hidden-lines .top,
.monaco-editor .diff-hidden-lines .bottom {
	transition: background-color 0.1s ease-out;
	height: 4px;
	background-color: transparent;
	background-clip: padding-box;
	border-bottom: 2px solid transparent;
	border-top: 4px solid transparent;
	/*cursor: n-resize;*/
}

.monaco-editor.draggingUnchangedRegion.canMoveTop:not(.canMoveBottom) *,
.monaco-editor .diff-hidden-lines .top.canMoveTop:not(.canMoveBottom),
.monaco-editor .diff-hidden-lines .bottom.canMoveTop:not(.canMoveBottom) {
	cursor: n-resize !important;
}

.monaco-editor.draggingUnchangedRegion:not(.canMoveTop).canMoveBottom *,
.monaco-editor .diff-hidden-lines .top:not(.canMoveTop).canMoveBottom,
.monaco-editor .diff-hidden-lines .bottom:not(.canMoveTop).canMoveBottom {
	cursor: s-resize !important;
}

.monaco-editor.draggingUnchangedRegion.canMoveTop.canMoveBottom *,
.monaco-editor .diff-hidden-lines .top.canMoveTop.canMoveBottom,
.monaco-editor .diff-hidden-lines .bottom.canMoveTop.canMoveBottom {
	cursor: ns-resize !important;
}

.monaco-editor .diff-hidden-lines .top {
	transform: translate(0px, 4px);
}

.monaco-editor .diff-hidden-lines .bottom {
	transform: translate(0px, -6px);
}

.monaco-editor .diff-unchanged-lines {
	background: var(--vscode-diffEditor-unchangedCodeBackground);
}

.monaco-editor .noModificationsOverlay {
	z-index: 1;
	background: var(--vscode-editor-background);

	display: flex;
	justify-content: center;
	align-items: center;
}


.monaco-editor .diff-hidden-lines .center {
	background: var(--vscode-diffEditor-unchangedRegionBackground);
	color: var(--vscode-diffEditor-unchangedRegionForeground);
	overflow: hidden;
	display: block;
	text-overflow: ellipsis;
	white-space: nowrap;

	height: 24px;
	box-shadow: inset 0 -5px 5px -7px var(--vscode-diffEditor-unchangedRegionShadow), inset 0 5px 5px -7px var(--vscode-diffEditor-unchangedRegionShadow);
}

.monaco-editor .diff-hidden-lines .center span.codicon {
	vertical-align: middle;
}

.monaco-editor .diff-hidden-lines .center a:hover .codicon {
	cursor: pointer;
	color: var(--vscode-editorLink-activeForeground) !important;
}

.monaco-editor .diff-hidden-lines div.breadcrumb-item {
	cursor: pointer;
}

.monaco-editor .diff-hidden-lines div.breadcrumb-item:hover {
	color: var(--vscode-editorLink-activeForeground);
}

.monaco-editor .movedOriginal {
	border: 2px solid var(--vscode-diffEditor-move-border);
}

.monaco-editor .movedModified {
	border: 2px solid var(--vscode-diffEditor-move-border);
}

.monaco-editor .movedOriginal.currentMove, .monaco-editor .movedModified.currentMove {
	border: 2px solid var(--vscode-diffEditor-moveActive-border);
}

.monaco-diff-editor .moved-blocks-lines path.currentMove {
	stroke: var(--vscode-diffEditor-moveActive-border);
}

.monaco-diff-editor .moved-blocks-lines path {
	pointer-events: visiblestroke;
}

.monaco-diff-editor .moved-blocks-lines .arrow {
	fill: var(--vscode-diffEditor-move-border);
}

.monaco-diff-editor .moved-blocks-lines .arrow.currentMove {
	fill: var(--vscode-diffEditor-moveActive-border);
}

.monaco-diff-editor .moved-blocks-lines .arrow-rectangle {
	fill: var(--vscode-editor-background);
}

.monaco-diff-editor .moved-blocks-lines {
	position: absolute;
	pointer-events: none;
}

.monaco-diff-editor .moved-blocks-lines path {
	fill: none;
	stroke: var(--vscode-diffEditor-move-border);
	stroke-width: 2;
}

.monaco-editor .char-delete.diff-range-empty {
	margin-left: -1px;
	border-left: solid var(--vscode-diffEditor-removedTextBackground) 3px;
}

.monaco-editor .char-insert.diff-range-empty {
	border-left: solid var(--vscode-diffEditor-insertedTextBackground) 3px;
}

.monaco-editor .fold-unchanged {
	cursor: pointer;
}

.monaco-diff-editor .diff-moved-code-block {
	display: flex;
	justify-content: flex-end;
	margin-top: -4px;
}

.monaco-diff-editor .diff-moved-code-block .action-bar .action-label.codicon {
	width: 12px;
	height: 12px;
	font-size: 12px;
}

/* ---------- DiffEditor ---------- */

.monaco-diff-editor .diffOverview {
	z-index: 9;
}

.monaco-diff-editor .diffOverview .diffViewport {
	z-index: 10;
}

/* colors not externalized: using transparancy on background */
.monaco-diff-editor.vs			.diffOverview { background: rgba(0, 0, 0, 0.03); }
.monaco-diff-editor.vs-dark		.diffOverview { background: rgba(255, 255, 255, 0.01); }

.monaco-scrollable-element.modified-in-monaco-diff-editor.vs		.scrollbar { background: rgba(0,0,0,0); }
.monaco-scrollable-element.modified-in-monaco-diff-editor.vs-dark	.scrollbar { background: rgba(0,0,0,0); }
.monaco-scrollable-element.modified-in-monaco-diff-editor.hc-black	.scrollbar { background: none; }
.monaco-scrollable-element.modified-in-monaco-diff-editor.hc-light	.scrollbar { background: none; }

.monaco-scrollable-element.modified-in-monaco-diff-editor .slider {
	z-index: 10;
}
.modified-in-monaco-diff-editor				.slider.active { background: rgba(171, 171, 171, .4); }
.modified-in-monaco-diff-editor.hc-black	.slider.active { background: none; }
.modified-in-monaco-diff-editor.hc-light	.slider.active { background: none; }

/* ---------- Diff ---------- */

.monaco-editor .insert-sign,
.monaco-diff-editor .insert-sign,
.monaco-editor .delete-sign,
.monaco-diff-editor .delete-sign {
	font-size: 11px !important;
	opacity: 0.7 !important;
	display: flex !important;
	align-items: center;
}
.monaco-editor.hc-black .insert-sign,
.monaco-diff-editor.hc-black .insert-sign,
.monaco-editor.hc-black .delete-sign,
.monaco-diff-editor.hc-black .delete-sign,
.monaco-editor.hc-light .insert-sign,
.monaco-diff-editor.hc-light .insert-sign,
.monaco-editor.hc-light .delete-sign,
.monaco-diff-editor.hc-light .delete-sign {
	opacity: 1;
}

.monaco-editor .inline-deleted-margin-view-zone {
	text-align: right;
}
.monaco-editor .inline-added-margin-view-zone {
	text-align: right;
}

.monaco-editor .arrow-revert-change {
	z-index: 10;
	position: absolute;
}

.monaco-editor .arrow-revert-change:hover {
	cursor: pointer;
}

/* ---------- Inline Diff ---------- */

.monaco-editor .view-zones .view-lines .view-line span {
	display: inline-block;
}

.monaco-editor .margin-view-zones .lightbulb-glyph:hover {
	cursor: pointer;
}

.monaco-editor .char-insert, .monaco-diff-editor .char-insert {
	background-color: var(--vscode-diffEditor-insertedTextBackground);
}

.monaco-editor .line-insert, .monaco-diff-editor .line-insert {
	background-color: var(--vscode-diffEditor-insertedLineBackground, var(--vscode-diffEditor-insertedTextBackground));
}

.monaco-editor .line-insert,
.monaco-editor .char-insert {
	box-sizing: border-box;
	border: 1px solid var(--vscode-diffEditor-insertedTextBorder);
}
.monaco-editor.hc-black .line-insert, .monaco-editor.hc-light .line-insert,
.monaco-editor.hc-black .char-insert, .monaco-editor.hc-light .char-insert {
	border-style: dashed;
}

.monaco-editor .line-delete,
.monaco-editor .char-delete {
	box-sizing: border-box;
	border: 1px solid var(--vscode-diffEditor-removedTextBorder);
}
.monaco-editor.hc-black .line-delete, .monaco-editor.hc-light .line-delete,
.monaco-editor.hc-black .char-delete, .monaco-editor.hc-light .char-delete {
	border-style: dashed;
}

.monaco-editor .inline-added-margin-view-zone,
.monaco-editor .gutter-insert, .monaco-diff-editor .gutter-insert {
	background-color: var(--vscode-diffEditorGutter-insertedLineBackground, var(--vscode-diffEditor-insertedLineBackground), var(--vscode-diffEditor-insertedTextBackground));
}

.monaco-editor .char-delete, .monaco-diff-editor .char-delete, .monaco-editor .inline-deleted-text {
	background-color: var(--vscode-diffEditor-removedTextBackground);
}

.monaco-editor .inline-deleted-text {
	text-decoration: line-through;
}

.monaco-editor .line-delete, .monaco-diff-editor .line-delete {
	background-color: var(--vscode-diffEditor-removedLineBackground, var(--vscode-diffEditor-removedTextBackground));
}

.monaco-editor .inline-deleted-margin-view-zone,
.monaco-editor .gutter-delete, .monaco-diff-editor .gutter-delete {
	background-color: var(--vscode-diffEditorGutter-removedLineBackground, var(--vscode-diffEditor-removedLineBackground), var(--vscode-diffEditor-removedTextBackground));
}

.monaco-diff-editor.side-by-side .editor.modified {
	box-shadow: -6px 0 5px -5px var(--vscode-scrollbar-shadow);
	border-left: 1px solid var(--vscode-diffEditor-border);
}

.monaco-diff-editor.side-by-side .editor.original {
	box-shadow: 6px 0 5px -5px var(--vscode-scrollbar-shadow);
	border-right: 1px solid var(--vscode-diffEditor-border);
}

.monaco-diff-editor .diffViewport {
	background: var(--vscode-scrollbarSlider-background);
}

.monaco-diff-editor .diffViewport:hover {
	background: var(--vscode-scrollbarSlider-hoverBackground);
}

.monaco-diff-editor .diffViewport:active {
	background: var(--vscode-scrollbarSlider-activeBackground);
}

.monaco-editor .diagonal-fill {
	background-image: linear-gradient(
		-45deg,
		var(--vscode-diffEditor-diagonalFill) 12.5%,
		#0000 12.5%, #0000 50%,
		var(--vscode-diffEditor-diagonalFill) 50%, var(--vscode-diffEditor-diagonalFill) 62.5%,
		#0000 62.5%, #0000 100%
	);
	background-size: 8px 8px;
}

.monaco-diff-editor .gutter {
	position: relative;
	overflow: hidden;
	flex-shrink: 0;
	flex-grow: 0;

	& > div {
		position: absolute;
	}

	.gutterItem {
		opacity: 0;
		transition: opacity 0.7s;

		&.showAlways {
			opacity: 1;
			transition: none;
		}

		&.noTransition {
			transition: none;
		}
	}

	&:hover .gutterItem {
		opacity: 1;
		transition: opacity 0.1s ease-in-out;
	}

	.gutterItem {
		.background {
			position: absolute;
			height: 100%;
			left: 50%;
			width: 1px;

			border-left: 2px var(--vscode-menu-border) solid;
		}

		.buttons {
			position: absolute;
			/*height: 100%;*/
			width: 100%;

			display: flex;
			justify-content: center;
			align-items: center;

			.monaco-toolbar {
				height: fit-content;
				.monaco-action-bar  {
					line-height: 1;

					.actions-container {
						width: fit-content;
						border-radius: 4px;
						background: var(--vscode-editorGutter-commentRangeForeground);

						.action-item {
							&:hover {
								background: var(--vscode-toolbar-hoverBackground);
							}

							.action-label {
								padding: 1px 2px;
							}
						}
					}
				}
			}
		}
	}
}


.monaco-diff-editor .diff-hidden-lines-compact {
	display: flex;
	height: 11px;
	.line-left, .line-right {
		height: 1px;
		border-top: 1px solid;
		border-color: var(--vscode-editorCodeLens-foreground);
		opacity: 0.5;
		margin: auto;
		width: 100%;
	}

	.line-left {
		width: 20px;
	}

	.text {
		color: var(--vscode-editorCodeLens-foreground);
		text-wrap: nowrap;
		font-size: 11px;
		line-height: 11px;
		margin: 0 4px;
	}
}
</style><style type="text/css">.monaco-component.diff-review{user-select:none;-webkit-user-select:none;z-index:99}.monaco-diff-editor .diff-review{position:absolute}.monaco-component.diff-review .diff-review-line-number{text-align:right;display:inline-block;color:var(--vscode-editorLineNumber-foreground)}.monaco-component.diff-review .diff-review-summary{padding-left:10px}.monaco-component.diff-review .diff-review-shadow{position:absolute;box-shadow:var(--vscode-scrollbar-shadow) 0 -6px 6px -6px inset}.monaco-component.diff-review .diff-review-row{white-space:pre}.monaco-component.diff-review .diff-review-table{display:table;min-width:100%}.monaco-component.diff-review .diff-review-row{display:table-row;width:100%}.monaco-component.diff-review .diff-review-spacer{display:inline-block;width:10px;vertical-align:middle}.monaco-component.diff-review .diff-review-spacer>.codicon{font-size:9px!important}.monaco-component.diff-review .diff-review-actions{display:inline-block;position:absolute;right:10px;top:2px;z-index:100}.monaco-component.diff-review .diff-review-actions .action-label{width:16px;height:16px;margin:2px 0}.monaco-component.diff-review .revertButton{cursor:pointer}</style><style type="text/css">.monaco-toolbar{height:100%}.monaco-toolbar .toolbar-toggle-more{display:inline-block;padding:0}</style><style type="text/css">/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-component.multiDiffEditor {
	background: var(--vscode-multiDiffEditor-background);

	position: relative;

	height: 100%;
	width: 100%;

	overflow-y: hidden;

	> div {
		position: absolute;
		top: 0px;
		left: 0px;

		height: 100%;
		width: 100%;

		&.placeholder {
			visibility: hidden;

			&.visible {
				visibility: visible;
			}

			display: grid;
			place-items: center;
			place-content: center;
		}
	}

	.active {
		--vscode-multiDiffEditor-border: var(--vscode-focusBorder);
	}

	.multiDiffEntry {
		display: flex;
		flex-direction: column;
		flex: 1;
		overflow: hidden;


		.collapse-button {
			margin: 0 5px;
			cursor: pointer;

			a {
				display: block;
			}
		}

		.header {
			z-index: 1000;
			background: var(--vscode-editor-background);

			&:not(.collapsed) .header-content {
				border-bottom: 1px solid var(--vscode-sideBarSectionHeader-border);
			}

			.header-content {
				margin: 8px 0px 0px 0px;
				padding: 4px 5px;

				border-top: 1px solid var(--vscode-multiDiffEditor-border);

				display: flex;
				align-items: center;

				color: var(--vscode-foreground);
				background: var(--vscode-multiDiffEditor-headerBackground);

				&.shadow {
					box-shadow: var(--vscode-scrollbar-shadow) 0px 6px 6px -6px;
				}

				.file-path {
					display: flex;
					flex: 1;
					min-width: 0;

					.title {
						font-size: 14px;
						line-height: 22px;

						&.original {
							flex: 1;
							min-width: 0;
							text-overflow: ellipsis;
						}
					}

					.status {
						font-weight: 600;
						opacity: 0.75;
						margin: 0px 10px;
						line-height: 22px;

						/*
							TODO@hediet: move colors from git extension to core!
						&.renamed {
							color: v ar(--vscode-gitDecoration-renamedResourceForeground);
						}

						&.deleted {
							color: v ar(--vscode-gitDecoration-deletedResourceForeground);
						}

						&.added {
							color: v ar(--vscode-gitDecoration-addedResourceForeground);
						}
						*/
					}
				}

				.actions {
					padding: 0 8px;
				}
			}


		}

		.editorParent {
			flex: 1;
			display: flex;
			flex-direction: column;

			border-bottom: 1px solid var(--vscode-multiDiffEditor-border);
			overflow: hidden;
		}

		.editorContainer {
			flex: 1;
		}
	}
}
</style><style type="text/css">.monaco-editor .selection-anchor{background-color:#007acc;width:2px!important}</style><style type="text/css">.monaco-editor .bracket-match{box-sizing:border-box;background-color:var(--vscode-editorBracketMatch-background);border:1px solid var(--vscode-editorBracketMatch-border)}</style><style type="text/css">.inline-editor-progress-decoration{display:inline-block;width:1em;height:1em}.inline-progress-widget{display:flex!important;justify-content:center;align-items:center}.inline-progress-widget .icon{font-size:80%!important}.inline-progress-widget:hover .icon{font-size:90%!important;animation:none}.inline-progress-widget:hover .icon::before{content:var(--vscode-icon-x-content);font-family:var(--vscode-icon-x-font-family)}</style><style type="text/css">.monaco-editor .monaco-editor-overlaymessage{padding-bottom:8px;z-index:10000}.monaco-editor .monaco-editor-overlaymessage.below{padding-bottom:0;padding-top:8px;z-index:10000}@keyframes fadeIn{from{opacity:0}to{opacity:1}}.monaco-editor .monaco-editor-overlaymessage.fadeIn{animation:fadeIn 150ms ease-out}@keyframes fadeOut{from{opacity:1}to{opacity:0}}.monaco-editor .monaco-editor-overlaymessage.fadeOut{animation:fadeOut .1s ease-out}.monaco-editor .monaco-editor-overlaymessage .message{padding:2px 4px;color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-inputValidation-infoBorder);border-radius:3px}.monaco-editor .monaco-editor-overlaymessage .message p{margin-block:0px}.monaco-editor .monaco-editor-overlaymessage .message a{color:var(--vscode-textLink-foreground)}.monaco-editor .monaco-editor-overlaymessage .message a:hover{color:var(--vscode-textLink-activeForeground)}.monaco-editor.hc-black .monaco-editor-overlaymessage .message,.monaco-editor.hc-light .monaco-editor-overlaymessage .message{border-width:2px}.monaco-editor .monaco-editor-overlaymessage .anchor{width:0!important;height:0!important;border-color:transparent;border-style:solid;z-index:1000;border-width:8px;position:absolute;left:2px}.monaco-editor .monaco-editor-overlaymessage .anchor.top{border-bottom-color:var(--vscode-inputValidation-infoBorder)}.monaco-editor .monaco-editor-overlaymessage .anchor.below{border-top-color:var(--vscode-inputValidation-infoBorder)}.monaco-editor .monaco-editor-overlaymessage.below .anchor.below,.monaco-editor .monaco-editor-overlaymessage:not(.below) .anchor.top{display:none}.monaco-editor .monaco-editor-overlaymessage.below .anchor.top{display:inherit;top:-8px}</style><style type="text/css">.post-edit-widget{box-shadow:0 0 8px 2px var(--vscode-widget-shadow);border:1px solid var(--vscode-widget-border,transparent);border-radius:4px;background-color:var(--vscode-editorWidget-background);overflow:hidden}.post-edit-widget .monaco-button{padding:2px;border:none;border-radius:0}.post-edit-widget .monaco-button:hover{background-color:var(--vscode-button-secondaryHoverBackground)!important}.post-edit-widget .monaco-button .codicon{margin:0}</style><style type="text/css">@font-face{font-family:codicon;font-display:block;src:url(./codicon.ttf) format("truetype")}.codicon[class*=codicon-]{font:normal normal normal 16px/1 codicon;display:inline-block;text-decoration:none;text-rendering:auto;text-align:center;text-transform:none;-webkit-font-smoothing:antialiased;-moz-osx-font-smoothing:grayscale;user-select:none;-webkit-user-select:none}</style><style type="text/css">.codicon-wrench-subaction{opacity:.5}@keyframes codicon-spin{100%{transform:rotate(360deg)}}.codicon-gear.codicon-modifier-spin,.codicon-loading.codicon-modifier-spin,.codicon-notebook-state-executing.codicon-modifier-spin,.codicon-sync.codicon-modifier-spin{animation:codicon-spin 1.5s steps(30) infinite}.codicon-modifier-disabled{opacity:.4}.codicon-loading,.codicon-tree-item-loading::before{animation-duration:1s!important;animation-timing-function:cubic-bezier(0.53,0.21,0.29,0.67)!important}</style><style type="text/css">.monaco-editor .codicon.codicon-symbol-array,.monaco-workbench .codicon.codicon-symbol-array{color:var(--vscode-symbolIcon-arrayForeground)}.monaco-editor .codicon.codicon-symbol-boolean,.monaco-workbench .codicon.codicon-symbol-boolean{color:var(--vscode-symbolIcon-booleanForeground)}.monaco-editor .codicon.codicon-symbol-class,.monaco-workbench .codicon.codicon-symbol-class{color:var(--vscode-symbolIcon-classForeground)}.monaco-editor .codicon.codicon-symbol-method,.monaco-workbench .codicon.codicon-symbol-method{color:var(--vscode-symbolIcon-methodForeground)}.monaco-editor .codicon.codicon-symbol-color,.monaco-workbench .codicon.codicon-symbol-color{color:var(--vscode-symbolIcon-colorForeground)}.monaco-editor .codicon.codicon-symbol-constant,.monaco-workbench .codicon.codicon-symbol-constant{color:var(--vscode-symbolIcon-constantForeground)}.monaco-editor .codicon.codicon-symbol-constructor,.monaco-workbench .codicon.codicon-symbol-constructor{color:var(--vscode-symbolIcon-constructorForeground)}.monaco-editor .codicon.codicon-symbol-enum,.monaco-editor .codicon.codicon-symbol-value,.monaco-workbench .codicon.codicon-symbol-enum,.monaco-workbench .codicon.codicon-symbol-value{color:var(--vscode-symbolIcon-enumeratorForeground)}.monaco-editor .codicon.codicon-symbol-enum-member,.monaco-workbench .codicon.codicon-symbol-enum-member{color:var(--vscode-symbolIcon-enumeratorMemberForeground)}.monaco-editor .codicon.codicon-symbol-event,.monaco-workbench .codicon.codicon-symbol-event{color:var(--vscode-symbolIcon-eventForeground)}.monaco-editor .codicon.codicon-symbol-field,.monaco-workbench .codicon.codicon-symbol-field{color:var(--vscode-symbolIcon-fieldForeground)}.monaco-editor .codicon.codicon-symbol-file,.monaco-workbench .codicon.codicon-symbol-file{color:var(--vscode-symbolIcon-fileForeground)}.monaco-editor .codicon.codicon-symbol-folder,.monaco-workbench .codicon.codicon-symbol-folder{color:var(--vscode-symbolIcon-folderForeground)}.monaco-editor .codicon.codicon-symbol-function,.monaco-workbench .codicon.codicon-symbol-function{color:var(--vscode-symbolIcon-functionForeground)}.monaco-editor .codicon.codicon-symbol-interface,.monaco-workbench .codicon.codicon-symbol-interface{color:var(--vscode-symbolIcon-interfaceForeground)}.monaco-editor .codicon.codicon-symbol-key,.monaco-workbench .codicon.codicon-symbol-key{color:var(--vscode-symbolIcon-keyForeground)}.monaco-editor .codicon.codicon-symbol-keyword,.monaco-workbench .codicon.codicon-symbol-keyword{color:var(--vscode-symbolIcon-keywordForeground)}.monaco-editor .codicon.codicon-symbol-module,.monaco-workbench .codicon.codicon-symbol-module{color:var(--vscode-symbolIcon-moduleForeground)}.monaco-editor .codicon.codicon-symbol-namespace,.monaco-workbench .codicon.codicon-symbol-namespace{color:var(--vscode-symbolIcon-namespaceForeground)}.monaco-editor .codicon.codicon-symbol-null,.monaco-workbench .codicon.codicon-symbol-null{color:var(--vscode-symbolIcon-nullForeground)}.monaco-editor .codicon.codicon-symbol-number,.monaco-workbench .codicon.codicon-symbol-number{color:var(--vscode-symbolIcon-numberForeground)}.monaco-editor .codicon.codicon-symbol-object,.monaco-workbench .codicon.codicon-symbol-object{color:var(--vscode-symbolIcon-objectForeground)}.monaco-editor .codicon.codicon-symbol-operator,.monaco-workbench .codicon.codicon-symbol-operator{color:var(--vscode-symbolIcon-operatorForeground)}.monaco-editor .codicon.codicon-symbol-package,.monaco-workbench .codicon.codicon-symbol-package{color:var(--vscode-symbolIcon-packageForeground)}.monaco-editor .codicon.codicon-symbol-property,.monaco-workbench .codicon.codicon-symbol-property{color:var(--vscode-symbolIcon-propertyForeground)}.monaco-editor .codicon.codicon-symbol-reference,.monaco-workbench .codicon.codicon-symbol-reference{color:var(--vscode-symbolIcon-referenceForeground)}.monaco-editor .codicon.codicon-symbol-snippet,.monaco-workbench .codicon.codicon-symbol-snippet{color:var(--vscode-symbolIcon-snippetForeground)}.monaco-editor .codicon.codicon-symbol-string,.monaco-workbench .codicon.codicon-symbol-string{color:var(--vscode-symbolIcon-stringForeground)}.monaco-editor .codicon.codicon-symbol-struct,.monaco-workbench .codicon.codicon-symbol-struct{color:var(--vscode-symbolIcon-structForeground)}.monaco-editor .codicon.codicon-symbol-text,.monaco-workbench .codicon.codicon-symbol-text{color:var(--vscode-symbolIcon-textForeground)}.monaco-editor .codicon.codicon-symbol-type-parameter,.monaco-workbench .codicon.codicon-symbol-type-parameter{color:var(--vscode-symbolIcon-typeParameterForeground)}.monaco-editor .codicon.codicon-symbol-unit,.monaco-workbench .codicon.codicon-symbol-unit{color:var(--vscode-symbolIcon-unitForeground)}.monaco-editor .codicon.codicon-symbol-variable,.monaco-workbench .codicon.codicon-symbol-variable{color:var(--vscode-symbolIcon-variableForeground)}</style><style type="text/css">.monaco-editor .lightBulbWidget{display:flex;align-items:center;justify-content:center}.monaco-editor .lightBulbWidget:hover{cursor:pointer}.monaco-editor .lightBulbWidget.codicon-light-bulb,.monaco-editor .lightBulbWidget.codicon-lightbulb-sparkle{color:var(--vscode-editorLightBulb-foreground)}.monaco-editor .lightBulbWidget.codicon-lightbulb-autofix,.monaco-editor .lightBulbWidget.codicon-lightbulb-sparkle-autofix{color:var(--vscode-editorLightBulbAutoFix-foreground,var(--vscode-editorLightBulb-foreground))}.monaco-editor .lightBulbWidget.codicon-sparkle-filled{color:var(--vscode-editorLightBulbAi-foreground,var(--vscode-icon-foreground))}.monaco-editor .lightBulbWidget:before{position:relative;z-index:2}.monaco-editor .lightBulbWidget:after{position:absolute;top:0;left:0;content:'';display:block;width:100%;height:100%;opacity:.3;z-index:1}.monaco-editor .glyph-margin-widgets .cgmr[class*=codicon-gutter-lightbulb]{display:block;cursor:pointer}.monaco-editor .glyph-margin-widgets .cgmr.codicon-gutter-lightbulb,.monaco-editor .glyph-margin-widgets .cgmr.codicon-gutter-lightbulb-sparkle{color:var(--vscode-editorLightBulb-foreground)}.monaco-editor .glyph-margin-widgets .cgmr.codicon-gutter-lightbulb-aifix-auto-fix,.monaco-editor .glyph-margin-widgets .cgmr.codicon-gutter-lightbulb-auto-fix{color:var(--vscode-editorLightBulbAutoFix-foreground,var(--vscode-editorLightBulb-foreground))}.monaco-editor .glyph-margin-widgets .cgmr.codicon-gutter-lightbulb-sparkle-filled{color:var(--vscode-editorLightBulbAi-foreground,var(--vscode-icon-foreground))}</style><style type="text/css">.action-widget{font-size:13px;border-radius:0;min-width:160px;max-width:80vw;z-index:40;display:block;width:100%;border:1px solid var(--vscode-editorWidget-border)!important;border-radius:5px;background-color:var(--vscode-editorActionList-background);color:var(--vscode-editorActionList-foreground);padding:4px;box-shadow:0 2px 8px var(--vscode-widget-shadow)}.context-view-block{position:fixed;cursor:initial;left:0;top:0;width:100%;height:100%;z-index:-1}.context-view-pointerBlock{position:fixed;cursor:initial;left:0;top:0;width:100%;height:100%;z-index:2}.action-widget .monaco-list{user-select:none;-webkit-user-select:none;border:none!important;border-width:0!important}.action-widget .monaco-list:focus:before{outline:0!important}.action-widget .monaco-list .monaco-scrollable-element{overflow:visible}.action-widget .monaco-list .monaco-list-row{padding:0 10px;white-space:nowrap;cursor:pointer;touch-action:none;width:100%;border-radius:4px}.action-widget .monaco-list .monaco-list-row.action.focused:not(.option-disabled){background-color:var(--vscode-editorActionList-focusBackground)!important;color:var(--vscode-editorActionList-focusForeground);outline:1px solid var(--vscode-menu-selectionBorder,transparent);outline-offset:-1px}.action-widget .monaco-list-row.group-header{color:var(--vscode-descriptionForeground)!important;font-weight:600;font-size:12px}.action-widget .monaco-list-row.group-header:not(:first-of-type){margin-top:2px}.action-widget .monaco-list .group-header,.action-widget .monaco-list .option-disabled,.action-widget .monaco-list .option-disabled .focused,.action-widget .monaco-list .option-disabled .focused:before,.action-widget .monaco-list .option-disabled:before{cursor:default!important;-webkit-touch-callout:none;-webkit-user-select:none;user-select:none;background-color:transparent!important;outline:0 solid!important}.action-widget .monaco-list-row.action{display:flex;gap:8px;align-items:center}.action-widget .monaco-list-row.action.option-disabled,.action-widget .monaco-list-row.action.option-disabled .codicon,.action-widget .monaco-list:focus .monaco-list-row.focused.action.option-disabled,.action-widget .monaco-list:not(.drop-target):not(.dragging) .monaco-list-row:hover:not(.selected):not(.focused).option-disabled{color:var(--vscode-disabledForeground)}.action-widget .monaco-list-row.action:not(.option-disabled) .codicon{color:inherit}.action-widget .monaco-list-row.action .title{flex:1;overflow:hidden;text-overflow:ellipsis}.action-widget .monaco-list-row.action .monaco-keybinding>.monaco-keybinding-key{background-color:var(--vscode-keybindingLabel-background);color:var(--vscode-keybindingLabel-foreground);border-style:solid;border-width:1px;border-radius:3px;border-color:var(--vscode-keybindingLabel-border);border-bottom-color:var(--vscode-keybindingLabel-bottomBorder);box-shadow:inset 0 -1px 0 var(--vscode-widget-shadow)}.action-widget .action-widget-action-bar{background-color:var(--vscode-editorActionList-background);border-top:1px solid var(--vscode-editorHoverWidget-border);margin-top:2px}.action-widget .action-widget-action-bar::before{display:block;content:"";width:100%}.action-widget .action-widget-action-bar .actions-container{padding:3px 8px 0}.action-widget-action-bar .action-label{color:var(--vscode-textLink-activeForeground);font-size:12px;line-height:22px;padding:0;pointer-events:all}.action-widget-action-bar .action-item{margin-right:16px;pointer-events:none}.action-widget-action-bar .action-label:hover{background-color:transparent!important}.monaco-action-bar .actions-container.highlight-toggled .action-label.checked{background:var(--vscode-actionBar-toggledBackground)!important}</style><style type="text/css">.monaco-editor .codelens-decoration{overflow:hidden;display:inline-block;text-overflow:ellipsis;white-space:nowrap;color:var(--vscode-editorCodeLens-foreground);line-height:var(--vscode-editorCodeLens-lineHeight);font-size:var(--vscode-editorCodeLens-fontSize);padding-right:calc(var(--vscode-editorCodeLens-fontSize)*.5);font-feature-settings:var(--vscode-editorCodeLens-fontFeatureSettings);font-family:var(--vscode-editorCodeLens-fontFamily),var(--vscode-editorCodeLens-fontFamilyDefault)}.monaco-editor .codelens-decoration>a,.monaco-editor .codelens-decoration>span{user-select:none;-webkit-user-select:none;white-space:nowrap;vertical-align:sub}.monaco-editor .codelens-decoration>a{text-decoration:none}.monaco-editor .codelens-decoration>a:hover{cursor:pointer;color:var(--vscode-editorLink-activeForeground)!important}.monaco-editor .codelens-decoration>a:hover .codicon{color:var(--vscode-editorLink-activeForeground)!important}.monaco-editor .codelens-decoration .codicon{vertical-align:middle;color:currentColor!important;color:var(--vscode-editorCodeLens-foreground);line-height:var(--vscode-editorCodeLens-lineHeight);font-size:var(--vscode-editorCodeLens-fontSize)}.monaco-editor .codelens-decoration>a:hover .codicon::before{cursor:pointer}@keyframes fadein{0%{opacity:0;visibility:visible}100%{opacity:1}}.monaco-editor .codelens-decoration.fadein{animation:fadein .1s linear}</style><style type="text/css">.colorpicker-widget{height:190px;user-select:none;-webkit-user-select:none}.colorpicker-color-decoration,.hc-light .colorpicker-color-decoration{border:solid .1em #000;box-sizing:border-box;margin:.1em .2em 0 .2em;width:.8em;height:.8em;line-height:.8em;display:inline-block;cursor:pointer}.hc-black .colorpicker-color-decoration,.vs-dark .colorpicker-color-decoration{border:solid .1em #eee}.colorpicker-header{display:flex;height:24px;position:relative;background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAAECAYAAACp8Z5+AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAZdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuMTZEaa/1AAAAHUlEQVQYV2PYvXu3JAi7uLiAMaYAjAGTQBPYLQkAa/0Zef3qRswAAAAASUVORK5CYII=");background-size:9px 9px;image-rendering:pixelated}.colorpicker-header .picked-color{width:240px;display:flex;align-items:center;justify-content:center;line-height:24px;cursor:pointer;color:#fff;flex:1;white-space:nowrap;overflow:hidden}.colorpicker-header .picked-color .picked-color-presentation{white-space:nowrap;margin-left:5px;margin-right:5px}.colorpicker-header .picked-color .codicon{color:inherit;font-size:14px}.colorpicker-header .picked-color.light{color:#000}.colorpicker-header .original-color{width:74px;z-index:inherit;cursor:pointer}.standalone-colorpicker{color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border)}.colorpicker-header.standalone-colorpicker{border-bottom:none}.colorpicker-header .close-button{cursor:pointer;background-color:var(--vscode-editorHoverWidget-background);border-left:1px solid var(--vscode-editorHoverWidget-border)}.colorpicker-header .close-button-inner-div{width:100%;height:100%;text-align:center}.colorpicker-header .close-button-inner-div:hover{background-color:var(--vscode-toolbar-hoverBackground)}.colorpicker-header .close-icon{padding:3px}.colorpicker-body{display:flex;padding:8px;position:relative}.colorpicker-body .saturation-wrap{overflow:hidden;height:150px;position:relative;min-width:220px;flex:1}.colorpicker-body .saturation-box{height:150px;position:absolute}.colorpicker-body .saturation-selection{width:9px;height:9px;margin:-5px 0 0 -5px;border:1px solid #fff;border-radius:100%;box-shadow:0 0 2px rgba(0,0,0,.8);position:absolute}.colorpicker-body .strip{width:25px;height:150px}.colorpicker-body .standalone-strip{width:25px;height:122px}.colorpicker-body .hue-strip{position:relative;margin-left:8px;cursor:grab;background:linear-gradient(to bottom,red 0,#ff0 17%,#0f0 33%,#0ff 50%,#00f 67%,#f0f 83%,red 100%)}.colorpicker-body .opacity-strip{position:relative;margin-left:8px;cursor:grab;background:url("data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAAQAAAAECAYAAACp8Z5+AAAAAXNSR0IArs4c6QAAAARnQU1BAACxjwv8YQUAAAAJcEhZcwAADsMAAA7DAcdvqGQAAAAZdEVYdFNvZnR3YXJlAHBhaW50Lm5ldCA0LjAuMTZEaa/1AAAAHUlEQVQYV2PYvXu3JAi7uLiAMaYAjAGTQBPYLQkAa/0Zef3qRswAAAAASUVORK5CYII=");background-size:9px 9px;image-rendering:pixelated}.colorpicker-body .strip.grabbing{cursor:grabbing}.colorpicker-body .slider{position:absolute;top:0;left:-2px;width:calc(100% + 4px);height:4px;box-sizing:border-box;border:1px solid rgba(255,255,255,.71);box-shadow:0 0 1px rgba(0,0,0,.85)}.colorpicker-body .strip .overlay{height:150px;pointer-events:none}.colorpicker-body .standalone-strip .standalone-overlay{height:122px;pointer-events:none}.standalone-colorpicker-body{display:block;border:1px solid transparent;border-bottom:1px solid var(--vscode-editorHoverWidget-border);overflow:hidden}.colorpicker-body .insert-button{position:absolute;height:20px;width:58px;padding:0;right:8px;bottom:8px;background:var(--vscode-button-background);color:var(--vscode-button-foreground);border-radius:2px;border:none;cursor:pointer}.colorpicker-body .insert-button:hover{background:var(--vscode-button-hoverBackground)}</style><style type="text/css">.monaco-editor .inlineSuggestionsHints.withBorder{z-index:39;color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border)}.monaco-editor .inlineSuggestionsHints a{color:var(--vscode-foreground)}.monaco-editor .inlineSuggestionsHints a:hover{color:var(--vscode-foreground)}.monaco-editor .inlineSuggestionsHints .keybinding{display:flex;margin-left:4px;opacity:.6}.monaco-editor .inlineSuggestionsHints .keybinding .monaco-keybinding-key{font-size:8px;padding:2px 3px}.monaco-editor .inlineSuggestionsHints .availableSuggestionCount a{display:flex;min-width:19px;justify-content:center}.monaco-editor .inlineSuggestionStatusBarItemLabel{margin-right:2px}</style><style type="text/css">.monaco-editor .peekview-widget .head{box-sizing:border-box;display:flex;justify-content:space-between;flex-wrap:nowrap}.monaco-editor .peekview-widget .head .peekview-title{display:flex;align-items:baseline;font-size:13px;margin-left:20px;min-width:0;text-overflow:ellipsis;overflow:hidden}.monaco-editor .peekview-widget .head .peekview-title.clickable{cursor:pointer}.monaco-editor .peekview-widget .head .peekview-title .dirname:not(:empty){font-size:.9em;margin-left:.5em}.monaco-editor .peekview-widget .head .peekview-title .meta{white-space:nowrap;overflow:hidden;text-overflow:ellipsis}.monaco-editor .peekview-widget .head .peekview-title .dirname{overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.monaco-editor .peekview-widget .head .peekview-title .filename{overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.monaco-editor .peekview-widget .head .peekview-title .meta:not(:empty)::before{content:'-';padding:0 .3em}.monaco-editor .peekview-widget .head .peekview-actions{flex:1;text-align:right;padding-right:2px}.monaco-editor .peekview-widget .head .peekview-actions>.monaco-action-bar{display:inline-block}.monaco-editor .peekview-widget .head .peekview-actions>.monaco-action-bar,.monaco-editor .peekview-widget .head .peekview-actions>.monaco-action-bar>.actions-container{height:100%}.monaco-editor .peekview-widget>.body{border-top:1px solid;position:relative}.monaco-editor .peekview-widget .head .peekview-title .codicon{margin-right:4px;align-self:center}.monaco-editor .peekview-widget .monaco-list .monaco-list-row.focused .codicon{color:inherit!important}</style><style type="text/css">.monaco-editor .zone-widget{position:absolute;z-index:10}.monaco-editor .zone-widget .zone-widget-container{border-top-style:solid;border-bottom-style:solid;border-top-width:0;border-bottom-width:0;position:relative}</style><style type="text/css">.monaco-editor .zone-widget .zone-widget-container.reference-zone-widget{border-top-width:1px;border-bottom-width:1px}.monaco-editor .reference-zone-widget .inline{display:inline-block;vertical-align:top}.monaco-editor .reference-zone-widget .messages{height:100%;width:100%;text-align:center;padding:3em 0}.monaco-editor .reference-zone-widget .ref-tree{line-height:23px;background-color:var(--vscode-peekViewResult-background);color:var(--vscode-peekViewResult-lineForeground)}.monaco-editor .reference-zone-widget .ref-tree .reference{text-overflow:ellipsis;overflow:hidden}.monaco-editor .reference-zone-widget .ref-tree .reference-file{display:inline-flex;width:100%;height:100%;color:var(--vscode-peekViewResult-fileForeground)}.monaco-editor .reference-zone-widget .ref-tree .monaco-list:focus .selected .reference-file{color:inherit!important}.monaco-editor .reference-zone-widget .ref-tree .monaco-list:focus .monaco-list-rows>.monaco-list-row.selected:not(.highlighted){background-color:var(--vscode-peekViewResult-selectionBackground);color:var(--vscode-peekViewResult-selectionForeground)!important}.monaco-editor .reference-zone-widget .ref-tree .reference-file .count{margin-right:12px;margin-left:auto}.monaco-editor .reference-zone-widget .ref-tree .referenceMatch .highlight{background-color:var(--vscode-peekViewResult-matchHighlightBackground)}.monaco-editor .reference-zone-widget .preview .reference-decoration{background-color:var(--vscode-peekViewEditor-matchHighlightBackground);border:2px solid var(--vscode-peekViewEditor-matchHighlightBorder);box-sizing:border-box}.monaco-editor .reference-zone-widget .preview .monaco-editor .inputarea.ime-input,.monaco-editor .reference-zone-widget .preview .monaco-editor .monaco-editor-background{background-color:var(--vscode-peekViewEditor-background)}.monaco-editor .reference-zone-widget .preview .monaco-editor .margin{background-color:var(--vscode-peekViewEditorGutter-background)}.monaco-editor.hc-black .reference-zone-widget .ref-tree .reference-file,.monaco-editor.hc-light .reference-zone-widget .ref-tree .reference-file{font-weight:700}.monaco-editor.hc-black .reference-zone-widget .ref-tree .referenceMatch .highlight,.monaco-editor.hc-light .reference-zone-widget .ref-tree .referenceMatch .highlight{border:1px dotted var(--vscode-contrastActiveBorder,transparent);box-sizing:border-box}</style><style type="text/css">.monaco-editor .hoverHighlight{background-color:var(--vscode-editor-hoverHighlightBackground)}.monaco-editor .monaco-hover-content{padding-right:2px;padding-bottom:2px;box-sizing:border-box}.monaco-editor .monaco-hover{color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border);border-radius:3px}.monaco-editor .monaco-hover a{color:var(--vscode-textLink-foreground)}.monaco-editor .monaco-hover a:hover{color:var(--vscode-textLink-activeForeground)}.monaco-editor .monaco-hover .hover-row{display:flex}.monaco-editor .monaco-hover .hover-row .hover-row-contents{min-width:0;display:flex;flex-direction:column}.monaco-editor .monaco-hover .hover-row .verbosity-actions{display:flex;flex-direction:column;padding-left:5px;padding-right:5px;justify-content:end;border-right:1px solid var(--vscode-editorHoverWidget-border)}.monaco-editor .monaco-hover .hover-row .verbosity-actions .codicon{cursor:pointer;font-size:11px}.monaco-editor .monaco-hover .hover-row .verbosity-actions .codicon.enabled{color:var(--vscode-textLink-foreground)}.monaco-editor .monaco-hover .hover-row .verbosity-actions .codicon.disabled{opacity:.6}.monaco-editor .monaco-hover .hover-row .actions{background-color:var(--vscode-editorHoverWidget-statusBarBackground)}.monaco-editor .monaco-hover code{background-color:var(--vscode-textCodeBlock-background)}</style><style type="text/css">.monaco-editor.hc-light .dnd-target,.monaco-editor.vs .dnd-target{border-right:2px dotted #000;color:#fff}.monaco-editor.vs-dark .dnd-target{border-right:2px dotted #aeafad;color:#51504f}.monaco-editor.hc-black .dnd-target{border-right:2px dotted #fff;color:#000}.monaco-editor.hc-black.mac.mouse-default .view-lines,.monaco-editor.hc-light.mac.mouse-default .view-lines,.monaco-editor.mouse-default .view-lines,.monaco-editor.vs-dark.mac.mouse-default .view-lines{cursor:default}.monaco-editor.hc-black.mac.mouse-copy .view-lines,.monaco-editor.hc-light.mac.mouse-copy .view-lines,.monaco-editor.mouse-copy .view-lines,.monaco-editor.vs-dark.mac.mouse-copy .view-lines{cursor:copy}</style><style type="text/css">.monaco-editor .findOptionsWidget{background-color:var(--vscode-editorWidget-background);color:var(--vscode-editorWidget-foreground);box-shadow:0 0 8px 2px var(--vscode-widget-shadow);border:2px solid var(--vscode-contrastBorder)}</style><style type="text/css">.monaco-editor .find-widget{position:absolute;z-index:35;height:33px;overflow:hidden;line-height:19px;transition:transform .2s linear;padding:0 4px;box-sizing:border-box;transform:translateY(calc(-100% - 10px));box-shadow:0 0 8px 2px var(--vscode-widget-shadow);color:var(--vscode-editorWidget-foreground);border-left:1px solid var(--vscode-widget-border);border-right:1px solid var(--vscode-widget-border);border-bottom:1px solid var(--vscode-widget-border);border-bottom-left-radius:4px;border-bottom-right-radius:4px;background-color:var(--vscode-editorWidget-background)}.monaco-workbench.reduce-motion .monaco-editor .find-widget{transition:transform 0s linear}.monaco-editor .find-widget textarea{margin:0}.monaco-editor .find-widget.hiddenEditor{display:none}.monaco-editor .find-widget.replaceToggled>.replace-part{display:flex}.monaco-editor .find-widget.visible{transform:translateY(0)}.monaco-editor .find-widget .monaco-inputbox.synthetic-focus{outline:1px solid -webkit-focus-ring-color;outline-offset:-1px;outline-color:var(--vscode-focusBorder)}.monaco-editor .find-widget .monaco-inputbox .input{background-color:transparent;min-height:0}.monaco-editor .find-widget .monaco-findInput .input{font-size:13px}.monaco-editor .find-widget>.find-part,.monaco-editor .find-widget>.replace-part{margin:3px 25px 0 17px;font-size:12px;display:flex}.monaco-editor .find-widget>.find-part .monaco-inputbox,.monaco-editor .find-widget>.replace-part .monaco-inputbox{min-height:25px}.monaco-editor .find-widget>.replace-part .monaco-inputbox>.ibwrapper>.mirror{padding-right:22px}.monaco-editor .find-widget>.find-part .monaco-inputbox>.ibwrapper>.input,.monaco-editor .find-widget>.find-part .monaco-inputbox>.ibwrapper>.mirror,.monaco-editor .find-widget>.replace-part .monaco-inputbox>.ibwrapper>.input,.monaco-editor .find-widget>.replace-part .monaco-inputbox>.ibwrapper>.mirror{padding-top:2px;padding-bottom:2px}.monaco-editor .find-widget>.find-part .find-actions{height:25px;display:flex;align-items:center}.monaco-editor .find-widget>.replace-part .replace-actions{height:25px;display:flex;align-items:center}.monaco-editor .find-widget .monaco-findInput{vertical-align:middle;display:flex;flex:1}.monaco-editor .find-widget .monaco-findInput .monaco-scrollable-element{width:100%}.monaco-editor .find-widget .monaco-findInput .monaco-scrollable-element .scrollbar.vertical{opacity:0}.monaco-editor .find-widget .matchesCount{display:flex;flex:initial;margin:0 0 0 3px;padding:2px 0 0 2px;height:25px;vertical-align:middle;box-sizing:border-box;text-align:center;line-height:23px}.monaco-editor .find-widget .button{width:16px;height:16px;padding:3px;border-radius:5px;display:flex;flex:initial;margin-left:3px;background-position:center center;background-repeat:no-repeat;cursor:pointer;display:flex;align-items:center;justify-content:center}.monaco-editor .find-widget .codicon-find-selection{width:22px;height:22px;padding:3px;border-radius:5px}.monaco-editor .find-widget .button.left{margin-left:0;margin-right:3px}.monaco-editor .find-widget .button.wide{width:auto;padding:1px 6px;top:-1px}.monaco-editor .find-widget .button.toggle{position:absolute;top:0;left:3px;width:18px;height:100%;border-radius:0;box-sizing:border-box}.monaco-editor .find-widget .button.toggle.disabled{display:none}.monaco-editor .find-widget .disabled{color:var(--vscode-disabledForeground);cursor:default}.monaco-editor .find-widget>.replace-part{display:none}.monaco-editor .find-widget>.replace-part>.monaco-findInput{position:relative;display:flex;vertical-align:middle;flex:auto;flex-grow:0;flex-shrink:0}.monaco-editor .find-widget>.replace-part>.monaco-findInput>.controls{position:absolute;top:3px;right:2px}.monaco-editor .find-widget.reduced-find-widget .matchesCount{display:none}.monaco-editor .find-widget.narrow-find-widget{max-width:257px!important}.monaco-editor .find-widget.collapsed-find-widget{max-width:170px!important}.monaco-editor .find-widget.collapsed-find-widget .button.next,.monaco-editor .find-widget.collapsed-find-widget .button.previous,.monaco-editor .find-widget.collapsed-find-widget .button.replace,.monaco-editor .find-widget.collapsed-find-widget .button.replace-all,.monaco-editor .find-widget.collapsed-find-widget>.find-part .monaco-findInput .controls{display:none}.monaco-editor .find-widget.no-results .matchesCount{color:var(--vscode-errorForeground)}.monaco-editor .findMatch{animation-duration:0;animation-name:inherit!important;background-color:var(--vscode-editor-findMatchHighlightBackground)}.monaco-editor .currentFindMatch{background-color:var(--vscode-editor-findMatchBackground);border:2px solid var(--vscode-editor-findMatchBorder);padding:1px;box-sizing:border-box}.monaco-editor .findScope{background-color:var(--vscode-editor-findRangeHighlightBackground)}.monaco-editor .find-widget .monaco-sash{left:0!important;background-color:var(--vscode-editorWidget-resizeBorder,var(--vscode-editorWidget-border))}.monaco-editor.hc-black .find-widget .button:before{position:relative;top:1px;left:2px}.monaco-editor .find-widget .button:not(.disabled):hover,.monaco-editor .find-widget .codicon-find-selection:hover{background-color:var(--vscode-toolbar-hoverBackground)!important}.monaco-editor.findMatch{background-color:var(--vscode-editor-findMatchHighlightBackground)}.monaco-editor.currentFindMatch{background-color:var(--vscode-editor-findMatchBackground)}.monaco-editor.findScope{background-color:var(--vscode-editor-findRangeHighlightBackground)}.monaco-editor.findMatch{background-color:var(--vscode-editorWidget-background)}.monaco-editor .find-widget>.button.codicon-widget-close{position:absolute;top:5px;right:4px}</style><style type="text/css">.monaco-editor .margin-view-overlays .codicon-folding-collapsed,.monaco-editor .margin-view-overlays .codicon-folding-expanded,.monaco-editor .margin-view-overlays .codicon-folding-manual-collapsed,.monaco-editor .margin-view-overlays .codicon-folding-manual-expanded{cursor:pointer;opacity:0;transition:opacity .5s;display:flex;align-items:center;justify-content:center;font-size:140%;margin-left:2px}.monaco-workbench.reduce-motion .monaco-editor .margin-view-overlays .codicon-folding-collapsed,.monaco-workbench.reduce-motion .monaco-editor .margin-view-overlays .codicon-folding-expanded,.monaco-workbench.reduce-motion .monaco-editor .margin-view-overlays .codicon-folding-manual-collapsed,.monaco-workbench.reduce-motion .monaco-editor .margin-view-overlays .codicon-folding-manual-expanded{transition:initial}.monaco-editor .margin-view-overlays .codicon.alwaysShowFoldIcons,.monaco-editor .margin-view-overlays .codicon.codicon-folding-collapsed,.monaco-editor .margin-view-overlays .codicon.codicon-folding-manual-collapsed,.monaco-editor .margin-view-overlays:hover .codicon{opacity:1}.monaco-editor .inline-folded:after{color:var(--vscode-editor-foldPlaceholderForeground);margin:.1em .2em 0 .2em;content:"\22EF";display:inline;line-height:1em;cursor:pointer}.monaco-editor .folded-background{background-color:var(--vscode-editor-foldBackground)}.monaco-editor .cldr.codicon.codicon-folding-collapsed,.monaco-editor .cldr.codicon.codicon-folding-expanded,.monaco-editor .cldr.codicon.codicon-folding-manual-collapsed,.monaco-editor .cldr.codicon.codicon-folding-manual-expanded{color:var(--vscode-editorGutter-foldingControlForeground)!important}</style><style type="text/css">.monaco-editor .suggest-preview-additional-widget{white-space:nowrap}.monaco-editor .suggest-preview-additional-widget .content-spacer{color:transparent;white-space:pre}.monaco-editor .suggest-preview-additional-widget .button{display:inline-block;cursor:pointer;text-decoration:underline;text-underline-position:under}.monaco-editor .ghost-text-hidden{opacity:0;font-size:0}.monaco-editor .ghost-text-decoration,.monaco-editor .suggest-preview-text .ghost-text{font-style:italic}.monaco-editor .inline-completion-text-to-replace{text-decoration:underline;text-underline-position:under}.monaco-editor .ghost-text-decoration,.monaco-editor .ghost-text-decoration-preview,.monaco-editor .suggest-preview-text .ghost-text{color:var(--vscode-editorGhostText-foreground)!important;background-color:var(--vscode-editorGhostText-background);border:1px solid var(--vscode-editorGhostText-border)}</style><style type="text/css">.monaco-editor .snippet-placeholder{min-width:2px;outline-style:solid;outline-width:1px;background-color:var(--vscode-editor-snippetTabstopHighlightBackground,transparent);outline-color:var(--vscode-editor-snippetTabstopHighlightBorder,transparent)}.monaco-editor .finish-snippet-placeholder{outline-style:solid;outline-width:1px;background-color:var(--vscode-editor-snippetFinalTabstopHighlightBackground,transparent);outline-color:var(--vscode-editor-snippetFinalTabstopHighlightBorder,transparent)}</style><style type="text/css">.monaco-editor .suggest-widget{width:430px;z-index:40;display:flex;flex-direction:column;border-radius:3px}.monaco-editor .suggest-widget.message{flex-direction:row;align-items:center}.monaco-editor .suggest-details,.monaco-editor .suggest-widget{flex:0 1 auto;width:100%;border-style:solid;border-width:1px;border-color:var(--vscode-editorSuggestWidget-border);background-color:var(--vscode-editorSuggestWidget-background)}.monaco-editor.hc-black .suggest-details,.monaco-editor.hc-black .suggest-widget,.monaco-editor.hc-light .suggest-details,.monaco-editor.hc-light .suggest-widget{border-width:2px}.monaco-editor .suggest-widget .suggest-status-bar{box-sizing:border-box;display:none;flex-flow:row nowrap;justify-content:space-between;width:100%;font-size:80%;padding:0 4px 0 4px;border-top:1px solid var(--vscode-editorSuggestWidget-border);overflow:hidden}.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar{display:flex}.monaco-editor .suggest-widget .suggest-status-bar .left{padding-right:8px}.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar .action-label{color:var(--vscode-editorSuggestWidgetStatus-foreground)}.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar .action-item:not(:last-of-type) .action-label{margin-right:0}.monaco-editor .suggest-widget.with-status-bar .suggest-status-bar .action-item:not(:last-of-type) .action-label::after{content:', ';margin-right:.3em}.monaco-editor .suggest-widget.with-status-bar .monaco-list .monaco-list-row.focused.string-label>.contents>.main>.right>.readMore,.monaco-editor .suggest-widget.with-status-bar .monaco-list .monaco-list-row>.contents>.main>.right>.readMore{display:none}.monaco-editor .suggest-widget.with-status-bar:not(.docs-side) .monaco-list .monaco-list-row:hover>.contents>.main>.right.can-expand-details>.details-label{width:100%}.monaco-editor .suggest-widget>.message{padding-left:22px}.monaco-editor .suggest-widget>.tree{height:100%;width:100%}.monaco-editor .suggest-widget .monaco-list{user-select:none;-webkit-user-select:none}.monaco-editor .suggest-widget .monaco-list .monaco-list-row{display:flex;-mox-box-sizing:border-box;box-sizing:border-box;padding-right:10px;background-repeat:no-repeat;background-position:2px 2px;white-space:nowrap;cursor:pointer;touch-action:none}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused{color:var(--vscode-editorSuggestWidget-selectedForeground)}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused .codicon{color:var(--vscode-editorSuggestWidget-selectedIconForeground)}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents{flex:1;height:100%;overflow:hidden;padding-left:2px}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main{display:flex;overflow:hidden;text-overflow:ellipsis;white-space:pre;justify-content:space-between}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left,.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right{display:flex}.monaco-editor .suggest-widget .monaco-list .monaco-list-row:not(.focused)>.contents>.main .monaco-icon-label{color:var(--vscode-editorSuggestWidget-foreground)}.monaco-editor .suggest-widget:not(.frozen) .monaco-highlighted-label .highlight{font-weight:700}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main .monaco-highlighted-label .highlight{color:var(--vscode-editorSuggestWidget-highlightForeground)}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused>.contents>.main .monaco-highlighted-label .highlight{color:var(--vscode-editorSuggestWidget-focusHighlightForeground)}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.codicon-close,.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.readMore::before{color:inherit;opacity:1;font-size:14px;cursor:pointer}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.codicon-close{position:absolute;top:6px;right:2px}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.codicon-close:hover,.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.readMore:hover{opacity:1}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label{opacity:.7}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left>.signature-label{overflow:hidden;text-overflow:ellipsis;opacity:.6}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left>.qualifier-label{margin-left:12px;opacity:.4;font-size:85%;line-height:initial;text-overflow:ellipsis;overflow:hidden;align-self:center}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label{font-size:85%;margin-left:1.1em;overflow:hidden;text-overflow:ellipsis;white-space:nowrap}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label>.monaco-tokenized-source{display:inline}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.details-label{display:none}.monaco-editor .suggest-widget:not(.shows-details) .monaco-list .monaco-list-row.focused>.contents>.main>.right>.details-label{display:inline}.monaco-editor .suggest-widget .monaco-list .monaco-list-row:not(.string-label)>.contents>.main>.right>.details-label,.monaco-editor .suggest-widget.docs-side .monaco-list .monaco-list-row.focused:not(.string-label)>.contents>.main>.right>.details-label{display:inline}.monaco-editor .suggest-widget:not(.docs-side) .monaco-list .monaco-list-row.focused:hover>.contents>.main>.right.can-expand-details>.details-label{width:calc(100% - 26px)}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left{flex-shrink:1;flex-grow:1;overflow:hidden}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.left>.monaco-icon-label{flex-shrink:0}.monaco-editor .suggest-widget .monaco-list .monaco-list-row:not(.string-label)>.contents>.main>.left>.monaco-icon-label{max-width:100%}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.string-label>.contents>.main>.left>.monaco-icon-label{flex-shrink:1}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right{overflow:hidden;flex-shrink:4;max-width:70%}.monaco-editor .suggest-widget .monaco-list .monaco-list-row>.contents>.main>.right>.readMore{display:inline-block;position:absolute;right:10px;width:18px;height:18px;visibility:hidden}.monaco-editor .suggest-widget.docs-side .monaco-list .monaco-list-row>.contents>.main>.right>.readMore{display:none!important}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.string-label>.contents>.main>.right>.readMore{display:none}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused.string-label>.contents>.main>.right>.readMore{display:inline-block}.monaco-editor .suggest-widget .monaco-list .monaco-list-row.focused:hover>.contents>.main>.right>.readMore{visibility:visible}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-icon-label.deprecated{opacity:.66;text-decoration:unset}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-icon-label.deprecated>.monaco-icon-label-container>.monaco-icon-name-container{text-decoration:line-through}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .monaco-icon-label::before{height:100%}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .icon{display:block;height:16px;width:16px;margin-left:2px;background-repeat:no-repeat;background-size:80%;background-position:center}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .icon.hide{display:none}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .suggest-icon{display:flex;align-items:center;margin-right:4px}.monaco-editor .suggest-widget.no-icons .monaco-list .monaco-list-row .icon,.monaco-editor .suggest-widget.no-icons .monaco-list .monaco-list-row .suggest-icon::before{display:none}.monaco-editor .suggest-widget .monaco-list .monaco-list-row .icon.customcolor .colorspan{margin:0 0 0 .3em;border:.1em solid #000;width:.7em;height:.7em;display:inline-block}.monaco-editor .suggest-details-container{z-index:41}.monaco-editor .suggest-details{display:flex;flex-direction:column;cursor:default;color:var(--vscode-editorSuggestWidget-foreground)}.monaco-editor .suggest-details.focused{border-color:var(--vscode-focusBorder)}.monaco-editor .suggest-details a{color:var(--vscode-textLink-foreground)}.monaco-editor .suggest-details a:hover{color:var(--vscode-textLink-activeForeground)}.monaco-editor .suggest-details code{background-color:var(--vscode-textCodeBlock-background)}.monaco-editor .suggest-details.no-docs{display:none}.monaco-editor .suggest-details>.monaco-scrollable-element{flex:1}.monaco-editor .suggest-details>.monaco-scrollable-element>.body{box-sizing:border-box;height:100%;width:100%}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.type{flex:2;overflow:hidden;text-overflow:ellipsis;opacity:.7;white-space:pre;margin:0 24px 0 0;padding:4px 0 12px 5px}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.header>.type.auto-wrap{white-space:normal;word-break:break-all}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs{margin:0;padding:4px 5px;white-space:pre-wrap}.monaco-editor .suggest-details.no-type>.monaco-scrollable-element>.body>.docs{margin-right:24px;overflow:hidden}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs{padding:0;white-space:initial;min-height:calc(1rem + 8px)}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>div,.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>span:not(:empty){padding:4px 5px}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>div>p:first-child{margin-top:0}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs>div>p:last-child{margin-bottom:0}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs .monaco-tokenized-source{white-space:pre}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs .code{white-space:pre-wrap;word-wrap:break-word}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>.docs.markdown-docs .codicon{vertical-align:sub}.monaco-editor .suggest-details>.monaco-scrollable-element>.body>p:empty{display:none}.monaco-editor .suggest-details code{border-radius:3px;padding:0 .4em}.monaco-editor .suggest-details ul{padding-left:20px}.monaco-editor .suggest-details ol{padding-left:20px}.monaco-editor .suggest-details p code{font-family:var(--monaco-monospace-font)}</style><style type="text/css">.monaco-editor .goto-definition-link{text-decoration:underline;cursor:pointer;color:var(--vscode-editorLink-activeForeground)!important}</style><style type="text/css">.monaco-editor .peekview-widget .head .peekview-title .severity-icon{display:inline-block;vertical-align:text-top;margin-right:4px}.monaco-editor .marker-widget{text-overflow:ellipsis;white-space:nowrap}.monaco-editor .marker-widget>.stale{opacity:.6;font-style:italic}.monaco-editor .marker-widget .title{display:inline-block;padding-right:5px}.monaco-editor .marker-widget .descriptioncontainer{position:absolute;white-space:pre;user-select:text;-webkit-user-select:text;padding:8px 12px 0 20px}.monaco-editor .marker-widget .descriptioncontainer .message{display:flex;flex-direction:column}.monaco-editor .marker-widget .descriptioncontainer .message .details{padding-left:6px}.monaco-editor .marker-widget .descriptioncontainer .message .source,.monaco-editor .marker-widget .descriptioncontainer .message span.code{opacity:.6}.monaco-editor .marker-widget .descriptioncontainer .message a.code-link{opacity:.6;color:inherit}.monaco-editor .marker-widget .descriptioncontainer .message a.code-link:before{content:'('}.monaco-editor .marker-widget .descriptioncontainer .message a.code-link:after{content:')'}.monaco-editor .marker-widget .descriptioncontainer .message a.code-link>span{text-decoration:underline;border-bottom:1px solid transparent;text-underline-position:under;color:var(--vscode-textLink-activeForeground)}.monaco-editor .marker-widget .descriptioncontainer .filename{cursor:pointer;color:var(--vscode-textLink-activeForeground)}</style><style type="text/css">.extension-editor .codicon.codicon-error,.extensions-viewlet>.extensions .codicon.codicon-error,.markers-panel .marker-icon .codicon.codicon-error,.markers-panel .marker-icon.error,.monaco-editor .zone-widget .codicon.codicon-error,.preferences-editor .codicon.codicon-error,.text-search-provider-messages .providerMessage .codicon.codicon-error{color:var(--vscode-problemsErrorIcon-foreground)}.extension-editor .codicon.codicon-warning,.extensions-viewlet>.extensions .codicon.codicon-warning,.markers-panel .marker-icon .codicon.codicon-warning,.markers-panel .marker-icon.warning,.monaco-editor .zone-widget .codicon.codicon-warning,.preferences-editor .codicon.codicon-warning,.text-search-provider-messages .providerMessage .codicon.codicon-warning{color:var(--vscode-problemsWarningIcon-foreground)}.extension-editor .codicon.codicon-info,.extensions-viewlet>.extensions .codicon.codicon-info,.markers-panel .marker-icon .codicon.codicon-info,.markers-panel .marker-icon.info,.monaco-editor .zone-widget .codicon.codicon-info,.preferences-editor .codicon.codicon-info,.text-search-provider-messages .providerMessage .codicon.codicon-info{color:var(--vscode-problemsInfoIcon-foreground)}</style><style type="text/css">.monaco-editor.vs .valueSetReplacement{outline:solid 2px var(--vscode-editorBracketMatch-border)}</style><style type="text/css">.monaco-editor .linked-editing-decoration{background-color:var(--vscode-editor-linkedEditingBackground);min-width:1px}</style><style type="text/css">.monaco-editor .detected-link,.monaco-editor .detected-link-active{text-decoration:underline;text-underline-position:under}.monaco-editor .detected-link-active{cursor:pointer;color:var(--vscode-editorLink-activeForeground)!important}</style><style type="text/css">.monaco-editor .focused .selectionHighlight{background-color:var(--vscode-editor-selectionHighlightBackground);box-sizing:border-box;border:1px solid var(--vscode-editor-selectionHighlightBorder)}.monaco-editor.hc-black .focused .selectionHighlight,.monaco-editor.hc-light .focused .selectionHighlight{border-style:dotted}.monaco-editor .wordHighlight{background-color:var(--vscode-editor-wordHighlightBackground);box-sizing:border-box;border:1px solid var(--vscode-editor-wordHighlightBorder)}.monaco-editor.hc-black .wordHighlight,.monaco-editor.hc-light .wordHighlight{border-style:dotted}.monaco-editor .wordHighlightStrong{background-color:var(--vscode-editor-wordHighlightStrongBackground);box-sizing:border-box;border:1px solid var(--vscode-editor-wordHighlightStrongBorder)}.monaco-editor.hc-black .wordHighlightStrong,.monaco-editor.hc-light .wordHighlightStrong{border-style:dotted}.monaco-editor .wordHighlightText{background-color:var(--vscode-editor-wordHighlightTextBackground);box-sizing:border-box;border:1px solid var(--vscode-editor-wordHighlightTextBorder)}.monaco-editor.hc-black .wordHighlightText,.monaco-editor.hc-light .wordHighlightText{border-style:dotted}</style><style type="text/css">.monaco-editor .inline-edit-remove{background-color:var(--vscode-editorGhostText-background);font-style:italic}.monaco-editor .inline-edit-hidden{opacity:0;font-size:0}.monaco-editor .inline-edit-decoration,.monaco-editor .suggest-preview-text .inline-edit{font-style:italic}.monaco-editor .inline-completion-text-to-replace{text-decoration:underline;text-underline-position:under}.monaco-editor .inline-edit-decoration,.monaco-editor .inline-edit-decoration-preview,.monaco-editor .suggest-preview-text .inline-edit{color:var(--vscode-editorGhostText-foreground)!important;background-color:var(--vscode-editorGhostText-background);border:1px solid var(--vscode-editorGhostText-border)}</style><style type="text/css">.monaco-editor .inlineEditHints.withBorder{z-index:39;color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border)}.monaco-editor .inlineEditHints a{color:var(--vscode-foreground)}.monaco-editor .inlineEditHints a:hover{color:var(--vscode-foreground)}.monaco-editor .inlineEditHints .keybinding{display:flex;margin-left:4px;opacity:.6}.monaco-editor .inlineEditHints .keybinding .monaco-keybinding-key{font-size:8px;padding:2px 3px}.monaco-editor .inlineEditStatusBarItemLabel{margin-right:2px}</style><style type="text/css">.monaco-editor .inlineEditSideBySide{z-index:39;color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border);white-space:pre}</style><style type="text/css">/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor div.inline-edits-widget {
	--widget-color: var(--vscode-notifications-background);

	.promptEditor .monaco-editor {
		--vscode-editor-placeholder-foreground: var(--vscode-editorGhostText-foreground);
	}

	.toolbar, .promptEditor {
		opacity: 0;
		transition: opacity 0.2s ease-in-out;
	}
	&:hover, &.focused {
		.toolbar, .promptEditor {
			opacity: 1;
		}
	}

	.preview .monaco-editor {

		.mtk1 {
			/*color: rgba(215, 215, 215, 0.452);*/
			color: var(--vscode-editorGhostText-foreground);
		}
		.view-overlays .current-line-exact {
			border: none;
		}

		.current-line-margin {
			border: none;
		}

		--vscode-editor-background: var(--widget-color);
	}

	svg {
		.gradient-start {
			stop-color: var(--vscode-editor-background);
		}

		.gradient-stop {
			stop-color: var(--widget-color);
		}
	}
}
</style><style type="text/css">.monaco-editor .parameter-hints-widget{z-index:39;display:flex;flex-direction:column;line-height:1.5em;cursor:default;color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border)}.hc-black .monaco-editor .parameter-hints-widget,.hc-light .monaco-editor .parameter-hints-widget{border-width:2px}.monaco-editor .parameter-hints-widget>.phwrapper{max-width:440px;display:flex;flex-direction:row}.monaco-editor .parameter-hints-widget.multiple{min-height:3.3em;padding:0}.monaco-editor .parameter-hints-widget.multiple .body::before{content:"";display:block;height:100%;position:absolute;opacity:.5;border-left:1px solid var(--vscode-editorHoverWidget-border)}.monaco-editor .parameter-hints-widget p,.monaco-editor .parameter-hints-widget ul{margin:8px 0}.monaco-editor .parameter-hints-widget .body,.monaco-editor .parameter-hints-widget .monaco-scrollable-element{display:flex;flex:1;flex-direction:column;min-height:100%}.monaco-editor .parameter-hints-widget .signature{padding:4px 5px;position:relative}.monaco-editor .parameter-hints-widget .signature.has-docs::after{content:"";display:block;position:absolute;left:0;width:100%;padding-top:4px;opacity:.5;border-bottom:1px solid var(--vscode-editorHoverWidget-border)}.monaco-editor .parameter-hints-widget .code{font-family:var(--vscode-parameterHintsWidget-editorFontFamily),var(--vscode-parameterHintsWidget-editorFontFamilyDefault)}.monaco-editor .parameter-hints-widget .docs{padding:0 10px 0 5px;white-space:pre-wrap}.monaco-editor .parameter-hints-widget .docs.empty{display:none}.monaco-editor .parameter-hints-widget .docs a{color:var(--vscode-textLink-foreground)}.monaco-editor .parameter-hints-widget .docs a:hover{color:var(--vscode-textLink-activeForeground);cursor:pointer}.monaco-editor .parameter-hints-widget .docs .markdown-docs{white-space:initial}.monaco-editor .parameter-hints-widget .docs code{font-family:var(--monaco-monospace-font);border-radius:3px;padding:0 .4em;background-color:var(--vscode-textCodeBlock-background)}.monaco-editor .parameter-hints-widget .docs .code,.monaco-editor .parameter-hints-widget .docs .monaco-tokenized-source{white-space:pre-wrap}.monaco-editor .parameter-hints-widget .controls{display:none;flex-direction:column;align-items:center;min-width:22px;justify-content:flex-end}.monaco-editor .parameter-hints-widget.multiple .controls{display:flex;padding:0 2px}.monaco-editor .parameter-hints-widget.multiple .button{width:16px;height:16px;background-repeat:no-repeat;cursor:pointer}.monaco-editor .parameter-hints-widget .button.previous{bottom:24px}.monaco-editor .parameter-hints-widget .overloads{text-align:center;height:12px;line-height:12px;font-family:var(--monaco-monospace-font)}.monaco-editor .parameter-hints-widget .signature .parameter.active{color:var(--vscode-editorHoverWidget-highlightForeground);font-weight:700}.monaco-editor .parameter-hints-widget .documentation-parameter>.parameter{font-weight:700;margin-right:.5em}</style><style type="text/css">/*---------------------------------------------------------------------------------------------
 *  Copyright (c) Microsoft Corporation. All rights reserved.
 *  Licensed under the MIT License. See License.txt in the project root for license information.
 *--------------------------------------------------------------------------------------------*/

.monaco-editor {
	--vscode-editor-placeholder-foreground: var(--vscode-editorGhostText-foreground);

	.editorPlaceholder {
		top: 0px;
		position: absolute;
		overflow: hidden;
		text-overflow: ellipsis;
		text-wrap: nowrap;
		pointer-events: none;

		color: var(--vscode-editor-placeholder-foreground);
	}
}
</style><style type="text/css">.monaco-editor .rename-box{z-index:100;color:inherit;border-radius:4px}.monaco-editor .rename-box.preview{padding:4px 4px 0 4px}.monaco-editor .rename-box .rename-input-with-button{padding:3px;border-radius:2px;width:calc(100% - 8px)}.monaco-editor .rename-box .rename-input{width:calc(100% - 8px);padding:0}.monaco-editor .rename-box .rename-input:focus{outline:0}.monaco-editor .rename-box .rename-suggestions-button{display:flex;align-items:center;padding:3px;background-color:transparent;border:none;border-radius:5px;cursor:pointer}.monaco-editor .rename-box .rename-suggestions-button:hover{background-color:var(--vscode-toolbar-hoverBackground)}.monaco-editor .rename-box .rename-candidate-list-container .monaco-list-row{border-radius:2px}.monaco-editor .rename-box .rename-label{display:none;opacity:.8}.monaco-editor .rename-box.preview .rename-label{display:inherit}</style><style type="text/css">.monaco-editor .sticky-widget{overflow:hidden}.monaco-editor .sticky-widget-line-numbers{float:left;background-color:inherit}.monaco-editor .sticky-widget-lines-scrollable{display:inline-block;position:absolute;overflow:hidden;width:var(--vscode-editorStickyScroll-scrollableWidth);background-color:inherit}.monaco-editor .sticky-widget-lines{position:absolute;background-color:inherit}.monaco-editor .sticky-line-content,.monaco-editor .sticky-line-number{color:var(--vscode-editorLineNumber-foreground);white-space:nowrap;display:inline-block;position:absolute;background-color:inherit}.monaco-editor .sticky-line-number .codicon-folding-collapsed,.monaco-editor .sticky-line-number .codicon-folding-expanded{float:right;transition:var(--vscode-editorStickyScroll-foldingOpacityTransition)}.monaco-editor .sticky-line-content{width:var(--vscode-editorStickyScroll-scrollableWidth);background-color:inherit;white-space:nowrap}.monaco-editor .sticky-line-number-inner{display:inline-block;text-align:right}.monaco-editor .sticky-widget{border-bottom:1px solid var(--vscode-editorStickyScroll-border)}.monaco-editor .sticky-line-content:hover{background-color:var(--vscode-editorStickyScrollHover-background);cursor:pointer}.monaco-editor .sticky-widget{width:100%;box-shadow:var(--vscode-editorStickyScroll-shadow) 0 4px 2px -2px;z-index:4;background-color:var(--vscode-editorStickyScroll-background);right:initial!important}.monaco-editor .sticky-widget.peek{background-color:var(--vscode-peekViewEditorStickyScroll-background)}</style><style type="text/css">.monaco-editor .unicode-highlight{border:1px solid var(--vscode-editorUnicodeHighlight-border);background-color:var(--vscode-editorUnicodeHighlight-background);box-sizing:border-box}</style><style type="text/css">.editor-banner{box-sizing:border-box;cursor:default;width:100%;font-size:12px;display:flex;overflow:visible;height:26px;background:var(--vscode-banner-background)}.editor-banner .icon-container{display:flex;flex-shrink:0;align-items:center;padding:0 6px 0 10px}.editor-banner .icon-container.custom-icon{background-repeat:no-repeat;background-position:center center;background-size:16px;width:16px;padding:0;margin:0 6px 0 10px}.editor-banner .message-container{display:flex;align-items:center;line-height:26px;text-overflow:ellipsis;white-space:nowrap;overflow:hidden}.editor-banner .message-container p{margin-block-start:0;margin-block-end:0}.editor-banner .message-actions-container{flex-grow:1;flex-shrink:0;line-height:26px;margin:0 4px}.editor-banner .message-actions-container a.monaco-button{width:inherit;margin:2px 8px;padding:0 12px}.editor-banner .message-actions-container a{padding:3px;margin-left:12px;text-decoration:underline}.editor-banner .action-container{padding:0 10px 0 6px}.editor-banner{background-color:var(--vscode-banner-background)}.editor-banner,.editor-banner .action-container .codicon,.editor-banner .message-actions-container .monaco-link{color:var(--vscode-banner-foreground)}.editor-banner .icon-container .codicon{color:var(--vscode-banner-iconForeground)}</style><style type="text/css">.monaco-link{color:var(--vscode-textLink-foreground)}.monaco-link:hover{color:var(--vscode-textLink-activeForeground)}</style><style type="text/css">.monaco-editor .iPadShowKeyboard{width:58px;min-width:0;height:36px;min-height:0;margin:0;padding:0;position:absolute;resize:none;overflow:hidden;background:url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIHZpZXdCb3g9IjAgMCA1MyAzNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwKSI+CjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNNDguMDM2NCA0LjAxMDQySDQuMDA3NzlMNC4wMDc3OSAzMi4wMjg2SDQ4LjAzNjRWNC4wMTA0MlpNNC4wMDc3OSAwLjAwNzgxMjVDMS43OTcyMSAwLjAwNzgxMjUgMC4wMDUxODc5OSAxLjc5OTg0IDAuMDA1MTg3OTkgNC4wMTA0MlYzMi4wMjg2QzAuMDA1MTg3OTkgMzQuMjM5MiAxLjc5NzIxIDM2LjAzMTIgNC4wMDc3OSAzNi4wMzEySDQ4LjAzNjRDNTAuMjQ3IDM2LjAzMTIgNTIuMDM5IDM0LjIzOTIgNTIuMDM5IDMyLjAyODZWNC4wMTA0MkM1Mi4wMzkgMS43OTk4NCA1MC4yNDcgMC4wMDc4MTI1IDQ4LjAzNjQgMC4wMDc4MTI1SDQuMDA3NzlaTTguMDEwNDIgOC4wMTMwMkgxMi4wMTNWMTIuMDE1Nkg4LjAxMDQyVjguMDEzMDJaTTIwLjAxODIgOC4wMTMwMkgxNi4wMTU2VjEyLjAxNTZIMjAuMDE4MlY4LjAxMzAyWk0yNC4wMjA4IDguMDEzMDJIMjguMDIzNFYxMi4wMTU2SDI0LjAyMDhWOC4wMTMwMlpNMzYuMDI4NiA4LjAxMzAySDMyLjAyNlYxMi4wMTU2SDM2LjAyODZWOC4wMTMwMlpNNDAuMDMxMiA4LjAxMzAySDQ0LjAzMzlWMTIuMDE1Nkg0MC4wMzEyVjguMDEzMDJaTTE2LjAxNTYgMTYuMDE4Mkg4LjAxMDQyVjIwLjAyMDhIMTYuMDE1NlYxNi4wMTgyWk0yMC4wMTgyIDE2LjAxODJIMjQuMDIwOFYyMC4wMjA4SDIwLjAxODJWMTYuMDE4MlpNMzIuMDI2IDE2LjAxODJIMjguMDIzNFYyMC4wMjA4SDMyLjAyNlYxNi4wMTgyWk00NC4wMzM5IDE2LjAxODJWMjAuMDIwOEgzNi4wMjg2VjE2LjAxODJINDQuMDMzOVpNMTIuMDEzIDI0LjAyMzRIOC4wMTA0MlYyOC4wMjZIMTIuMDEzVjI0LjAyMzRaTTE2LjAxNTYgMjQuMDIzNEgzNi4wMjg2VjI4LjAyNkgxNi4wMTU2VjI0LjAyMzRaTTQ0LjAzMzkgMjQuMDIzNEg0MC4wMzEyVjI4LjAyNkg0NC4wMzM5VjI0LjAyMzRaIiBmaWxsPSIjNDI0MjQyIi8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDAiPgo8cmVjdCB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIGZpbGw9IndoaXRlIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==") center center no-repeat;border:4px solid #f6f6f6;border-radius:4px}.monaco-editor.vs-dark .iPadShowKeyboard{background:url("data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIHZpZXdCb3g9IjAgMCA1MyAzNiIgZmlsbD0ibm9uZSIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj4KPGcgY2xpcC1wYXRoPSJ1cmwoI2NsaXAwKSI+CjxwYXRoIGZpbGwtcnVsZT0iZXZlbm9kZCIgY2xpcC1ydWxlPSJldmVub2RkIiBkPSJNNDguMDM2NCA0LjAxMDQySDQuMDA3NzlMNC4wMDc3OSAzMi4wMjg2SDQ4LjAzNjRWNC4wMTA0MlpNNC4wMDc3OSAwLjAwNzgxMjVDMS43OTcyMSAwLjAwNzgxMjUgMC4wMDUxODc5OSAxLjc5OTg0IDAuMDA1MTg3OTkgNC4wMTA0MlYzMi4wMjg2QzAuMDA1MTg3OTkgMzQuMjM5MiAxLjc5NzIxIDM2LjAzMTIgNC4wMDc3OSAzNi4wMzEySDQ4LjAzNjRDNTAuMjQ3IDM2LjAzMTIgNTIuMDM5IDM0LjIzOTIgNTIuMDM5IDMyLjAyODZWNC4wMTA0MkM1Mi4wMzkgMS43OTk4NCA1MC4yNDcgMC4wMDc4MTI1IDQ4LjAzNjQgMC4wMDc4MTI1SDQuMDA3NzlaTTguMDEwNDIgOC4wMTMwMkgxMi4wMTNWMTIuMDE1Nkg4LjAxMDQyVjguMDEzMDJaTTIwLjAxODIgOC4wMTMwMkgxNi4wMTU2VjEyLjAxNTZIMjAuMDE4MlY4LjAxMzAyWk0yNC4wMjA4IDguMDEzMDJIMjguMDIzNFYxMi4wMTU2SDI0LjAyMDhWOC4wMTMwMlpNMzYuMDI4NiA4LjAxMzAySDMyLjAyNlYxMi4wMTU2SDM2LjAyODZWOC4wMTMwMlpNNDAuMDMxMiA4LjAxMzAySDQ0LjAzMzlWMTIuMDE1Nkg0MC4wMzEyVjguMDEzMDJaTTE2LjAxNTYgMTYuMDE4Mkg4LjAxMDQyVjIwLjAyMDhIMTYuMDE1NlYxNi4wMTgyWk0yMC4wMTgyIDE2LjAxODJIMjQuMDIwOFYyMC4wMjA4SDIwLjAxODJWMTYuMDE4MlpNMzIuMDI2IDE2LjAxODJIMjguMDIzNFYyMC4wMjA4SDMyLjAyNlYxNi4wMTgyWk00NC4wMzM5IDE2LjAxODJWMjAuMDIwOEgzNi4wMjg2VjE2LjAxODJINDQuMDMzOVpNMTIuMDEzIDI0LjAyMzRIOC4wMTA0MlYyOC4wMjZIMTIuMDEzVjI0LjAyMzRaTTE2LjAxNTYgMjQuMDIzNEgzNi4wMjg2VjI4LjAyNkgxNi4wMTU2VjI0LjAyMzRaTTQ0LjAzMzkgMjQuMDIzNEg0MC4wMzEyVjI4LjAyNkg0NC4wMzM5VjI0LjAyMzRaIiBmaWxsPSIjQzVDNUM1Ii8+CjwvZz4KPGRlZnM+CjxjbGlwUGF0aCBpZD0iY2xpcDAiPgo8cmVjdCB3aWR0aD0iNTMiIGhlaWdodD0iMzYiIGZpbGw9IndoaXRlIi8+CjwvY2xpcFBhdGg+CjwvZGVmcz4KPC9zdmc+Cg==") center center no-repeat;border:4px solid #252526}</style><style type="text/css">.monaco-editor .tokens-inspect-widget{z-index:50;user-select:text;-webkit-user-select:text;padding:10px;color:var(--vscode-editorHoverWidget-foreground);background-color:var(--vscode-editorHoverWidget-background);border:1px solid var(--vscode-editorHoverWidget-border)}.monaco-editor.hc-black .tokens-inspect-widget,.monaco-editor.hc-light .tokens-inspect-widget{border-width:2px}.monaco-editor .tokens-inspect-widget .tokens-inspect-separator{height:1px;border:0;background-color:var(--vscode-editorHoverWidget-border)}.monaco-editor .tokens-inspect-widget .tm-token{font-family:var(--monaco-monospace-font)}.monaco-editor .tokens-inspect-widget .tm-token-length{font-weight:400;font-size:60%;float:right}.monaco-editor .tokens-inspect-widget .tm-metadata-table{width:100%}.monaco-editor .tokens-inspect-widget .tm-metadata-value{font-family:var(--monaco-monospace-font);text-align:right}.monaco-editor .tokens-inspect-widget .tm-token-type{font-family:var(--monaco-monospace-font)}</style><style type="text/css" media="screen" class="monaco-colors">.codicon-add:before { content: '\ea60'; }
.codicon-plus:before { content: '\ea60'; }
.codicon-gist-new:before { content: '\ea60'; }
.codicon-repo-create:before { content: '\ea60'; }
.codicon-lightbulb:before { content: '\ea61'; }
.codicon-light-bulb:before { content: '\ea61'; }
.codicon-repo:before { content: '\ea62'; }
.codicon-repo-delete:before { content: '\ea62'; }
.codicon-gist-fork:before { content: '\ea63'; }
.codicon-repo-forked:before { content: '\ea63'; }
.codicon-git-pull-request:before { content: '\ea64'; }
.codicon-git-pull-request-abandoned:before { content: '\ea64'; }
.codicon-record-keys:before { content: '\ea65'; }
.codicon-keyboard:before { content: '\ea65'; }
.codicon-tag:before { content: '\ea66'; }
.codicon-git-pull-request-label:before { content: '\ea66'; }
.codicon-tag-add:before { content: '\ea66'; }
.codicon-tag-remove:before { content: '\ea66'; }
.codicon-person:before { content: '\ea67'; }
.codicon-person-follow:before { content: '\ea67'; }
.codicon-person-outline:before { content: '\ea67'; }
.codicon-person-filled:before { content: '\ea67'; }
.codicon-git-branch:before { content: '\ea68'; }
.codicon-git-branch-create:before { content: '\ea68'; }
.codicon-git-branch-delete:before { content: '\ea68'; }
.codicon-source-control:before { content: '\ea68'; }
.codicon-mirror:before { content: '\ea69'; }
.codicon-mirror-public:before { content: '\ea69'; }
.codicon-star:before { content: '\ea6a'; }
.codicon-star-add:before { content: '\ea6a'; }
.codicon-star-delete:before { content: '\ea6a'; }
.codicon-star-empty:before { content: '\ea6a'; }
.codicon-comment:before { content: '\ea6b'; }
.codicon-comment-add:before { content: '\ea6b'; }
.codicon-alert:before { content: '\ea6c'; }
.codicon-warning:before { content: '\ea6c'; }
.codicon-search:before { content: '\ea6d'; }
.codicon-search-save:before { content: '\ea6d'; }
.codicon-log-out:before { content: '\ea6e'; }
.codicon-sign-out:before { content: '\ea6e'; }
.codicon-log-in:before { content: '\ea6f'; }
.codicon-sign-in:before { content: '\ea6f'; }
.codicon-eye:before { content: '\ea70'; }
.codicon-eye-unwatch:before { content: '\ea70'; }
.codicon-eye-watch:before { content: '\ea70'; }
.codicon-circle-filled:before { content: '\ea71'; }
.codicon-primitive-dot:before { content: '\ea71'; }
.codicon-close-dirty:before { content: '\ea71'; }
.codicon-debug-breakpoint:before { content: '\ea71'; }
.codicon-debug-breakpoint-disabled:before { content: '\ea71'; }
.codicon-debug-hint:before { content: '\ea71'; }
.codicon-terminal-decoration-success:before { content: '\ea71'; }
.codicon-primitive-square:before { content: '\ea72'; }
.codicon-edit:before { content: '\ea73'; }
.codicon-pencil:before { content: '\ea73'; }
.codicon-info:before { content: '\ea74'; }
.codicon-issue-opened:before { content: '\ea74'; }
.codicon-gist-private:before { content: '\ea75'; }
.codicon-git-fork-private:before { content: '\ea75'; }
.codicon-lock:before { content: '\ea75'; }
.codicon-mirror-private:before { content: '\ea75'; }
.codicon-close:before { content: '\ea76'; }
.codicon-remove-close:before { content: '\ea76'; }
.codicon-x:before { content: '\ea76'; }
.codicon-repo-sync:before { content: '\ea77'; }
.codicon-sync:before { content: '\ea77'; }
.codicon-clone:before { content: '\ea78'; }
.codicon-desktop-download:before { content: '\ea78'; }
.codicon-beaker:before { content: '\ea79'; }
.codicon-microscope:before { content: '\ea79'; }
.codicon-vm:before { content: '\ea7a'; }
.codicon-device-desktop:before { content: '\ea7a'; }
.codicon-file:before { content: '\ea7b'; }
.codicon-file-text:before { content: '\ea7b'; }
.codicon-more:before { content: '\ea7c'; }
.codicon-ellipsis:before { content: '\ea7c'; }
.codicon-kebab-horizontal:before { content: '\ea7c'; }
.codicon-mail-reply:before { content: '\ea7d'; }
.codicon-reply:before { content: '\ea7d'; }
.codicon-organization:before { content: '\ea7e'; }
.codicon-organization-filled:before { content: '\ea7e'; }
.codicon-organization-outline:before { content: '\ea7e'; }
.codicon-new-file:before { content: '\ea7f'; }
.codicon-file-add:before { content: '\ea7f'; }
.codicon-new-folder:before { content: '\ea80'; }
.codicon-file-directory-create:before { content: '\ea80'; }
.codicon-trash:before { content: '\ea81'; }
.codicon-trashcan:before { content: '\ea81'; }
.codicon-history:before { content: '\ea82'; }
.codicon-clock:before { content: '\ea82'; }
.codicon-folder:before { content: '\ea83'; }
.codicon-file-directory:before { content: '\ea83'; }
.codicon-symbol-folder:before { content: '\ea83'; }
.codicon-logo-github:before { content: '\ea84'; }
.codicon-mark-github:before { content: '\ea84'; }
.codicon-github:before { content: '\ea84'; }
.codicon-terminal:before { content: '\ea85'; }
.codicon-console:before { content: '\ea85'; }
.codicon-repl:before { content: '\ea85'; }
.codicon-zap:before { content: '\ea86'; }
.codicon-symbol-event:before { content: '\ea86'; }
.codicon-error:before { content: '\ea87'; }
.codicon-stop:before { content: '\ea87'; }
.codicon-variable:before { content: '\ea88'; }
.codicon-symbol-variable:before { content: '\ea88'; }
.codicon-array:before { content: '\ea8a'; }
.codicon-symbol-array:before { content: '\ea8a'; }
.codicon-symbol-module:before { content: '\ea8b'; }
.codicon-symbol-package:before { content: '\ea8b'; }
.codicon-symbol-namespace:before { content: '\ea8b'; }
.codicon-symbol-object:before { content: '\ea8b'; }
.codicon-symbol-method:before { content: '\ea8c'; }
.codicon-symbol-function:before { content: '\ea8c'; }
.codicon-symbol-constructor:before { content: '\ea8c'; }
.codicon-symbol-boolean:before { content: '\ea8f'; }
.codicon-symbol-null:before { content: '\ea8f'; }
.codicon-symbol-numeric:before { content: '\ea90'; }
.codicon-symbol-number:before { content: '\ea90'; }
.codicon-symbol-structure:before { content: '\ea91'; }
.codicon-symbol-struct:before { content: '\ea91'; }
.codicon-symbol-parameter:before { content: '\ea92'; }
.codicon-symbol-type-parameter:before { content: '\ea92'; }
.codicon-symbol-key:before { content: '\ea93'; }
.codicon-symbol-text:before { content: '\ea93'; }
.codicon-symbol-reference:before { content: '\ea94'; }
.codicon-go-to-file:before { content: '\ea94'; }
.codicon-symbol-enum:before { content: '\ea95'; }
.codicon-symbol-value:before { content: '\ea95'; }
.codicon-symbol-ruler:before { content: '\ea96'; }
.codicon-symbol-unit:before { content: '\ea96'; }
.codicon-activate-breakpoints:before { content: '\ea97'; }
.codicon-archive:before { content: '\ea98'; }
.codicon-arrow-both:before { content: '\ea99'; }
.codicon-arrow-down:before { content: '\ea9a'; }
.codicon-arrow-left:before { content: '\ea9b'; }
.codicon-arrow-right:before { content: '\ea9c'; }
.codicon-arrow-small-down:before { content: '\ea9d'; }
.codicon-arrow-small-left:before { content: '\ea9e'; }
.codicon-arrow-small-right:before { content: '\ea9f'; }
.codicon-arrow-small-up:before { content: '\eaa0'; }
.codicon-arrow-up:before { content: '\eaa1'; }
.codicon-bell:before { content: '\eaa2'; }
.codicon-bold:before { content: '\eaa3'; }
.codicon-book:before { content: '\eaa4'; }
.codicon-bookmark:before { content: '\eaa5'; }
.codicon-debug-breakpoint-conditional-unverified:before { content: '\eaa6'; }
.codicon-debug-breakpoint-conditional:before { content: '\eaa7'; }
.codicon-debug-breakpoint-conditional-disabled:before { content: '\eaa7'; }
.codicon-debug-breakpoint-data-unverified:before { content: '\eaa8'; }
.codicon-debug-breakpoint-data:before { content: '\eaa9'; }
.codicon-debug-breakpoint-data-disabled:before { content: '\eaa9'; }
.codicon-debug-breakpoint-log-unverified:before { content: '\eaaa'; }
.codicon-debug-breakpoint-log:before { content: '\eaab'; }
.codicon-debug-breakpoint-log-disabled:before { content: '\eaab'; }
.codicon-briefcase:before { content: '\eaac'; }
.codicon-broadcast:before { content: '\eaad'; }
.codicon-browser:before { content: '\eaae'; }
.codicon-bug:before { content: '\eaaf'; }
.codicon-calendar:before { content: '\eab0'; }
.codicon-case-sensitive:before { content: '\eab1'; }
.codicon-check:before { content: '\eab2'; }
.codicon-checklist:before { content: '\eab3'; }
.codicon-chevron-down:before { content: '\eab4'; }
.codicon-chevron-left:before { content: '\eab5'; }
.codicon-chevron-right:before { content: '\eab6'; }
.codicon-chevron-up:before { content: '\eab7'; }
.codicon-chrome-close:before { content: '\eab8'; }
.codicon-chrome-maximize:before { content: '\eab9'; }
.codicon-chrome-minimize:before { content: '\eaba'; }
.codicon-chrome-restore:before { content: '\eabb'; }
.codicon-circle-outline:before { content: '\eabc'; }
.codicon-circle:before { content: '\eabc'; }
.codicon-debug-breakpoint-unverified:before { content: '\eabc'; }
.codicon-terminal-decoration-incomplete:before { content: '\eabc'; }
.codicon-circle-slash:before { content: '\eabd'; }
.codicon-circuit-board:before { content: '\eabe'; }
.codicon-clear-all:before { content: '\eabf'; }
.codicon-clippy:before { content: '\eac0'; }
.codicon-close-all:before { content: '\eac1'; }
.codicon-cloud-download:before { content: '\eac2'; }
.codicon-cloud-upload:before { content: '\eac3'; }
.codicon-code:before { content: '\eac4'; }
.codicon-collapse-all:before { content: '\eac5'; }
.codicon-color-mode:before { content: '\eac6'; }
.codicon-comment-discussion:before { content: '\eac7'; }
.codicon-credit-card:before { content: '\eac9'; }
.codicon-dash:before { content: '\eacc'; }
.codicon-dashboard:before { content: '\eacd'; }
.codicon-database:before { content: '\eace'; }
.codicon-debug-continue:before { content: '\eacf'; }
.codicon-debug-disconnect:before { content: '\ead0'; }
.codicon-debug-pause:before { content: '\ead1'; }
.codicon-debug-restart:before { content: '\ead2'; }
.codicon-debug-start:before { content: '\ead3'; }
.codicon-debug-step-into:before { content: '\ead4'; }
.codicon-debug-step-out:before { content: '\ead5'; }
.codicon-debug-step-over:before { content: '\ead6'; }
.codicon-debug-stop:before { content: '\ead7'; }
.codicon-debug:before { content: '\ead8'; }
.codicon-device-camera-video:before { content: '\ead9'; }
.codicon-device-camera:before { content: '\eada'; }
.codicon-device-mobile:before { content: '\eadb'; }
.codicon-diff-added:before { content: '\eadc'; }
.codicon-diff-ignored:before { content: '\eadd'; }
.codicon-diff-modified:before { content: '\eade'; }
.codicon-diff-removed:before { content: '\eadf'; }
.codicon-diff-renamed:before { content: '\eae0'; }
.codicon-diff:before { content: '\eae1'; }
.codicon-diff-sidebyside:before { content: '\eae1'; }
.codicon-discard:before { content: '\eae2'; }
.codicon-editor-layout:before { content: '\eae3'; }
.codicon-empty-window:before { content: '\eae4'; }
.codicon-exclude:before { content: '\eae5'; }
.codicon-extensions:before { content: '\eae6'; }
.codicon-eye-closed:before { content: '\eae7'; }
.codicon-file-binary:before { content: '\eae8'; }
.codicon-file-code:before { content: '\eae9'; }
.codicon-file-media:before { content: '\eaea'; }
.codicon-file-pdf:before { content: '\eaeb'; }
.codicon-file-submodule:before { content: '\eaec'; }
.codicon-file-symlink-directory:before { content: '\eaed'; }
.codicon-file-symlink-file:before { content: '\eaee'; }
.codicon-file-zip:before { content: '\eaef'; }
.codicon-files:before { content: '\eaf0'; }
.codicon-filter:before { content: '\eaf1'; }
.codicon-flame:before { content: '\eaf2'; }
.codicon-fold-down:before { content: '\eaf3'; }
.codicon-fold-up:before { content: '\eaf4'; }
.codicon-fold:before { content: '\eaf5'; }
.codicon-folder-active:before { content: '\eaf6'; }
.codicon-folder-opened:before { content: '\eaf7'; }
.codicon-gear:before { content: '\eaf8'; }
.codicon-gift:before { content: '\eaf9'; }
.codicon-gist-secret:before { content: '\eafa'; }
.codicon-gist:before { content: '\eafb'; }
.codicon-git-commit:before { content: '\eafc'; }
.codicon-git-compare:before { content: '\eafd'; }
.codicon-compare-changes:before { content: '\eafd'; }
.codicon-git-merge:before { content: '\eafe'; }
.codicon-github-action:before { content: '\eaff'; }
.codicon-github-alt:before { content: '\eb00'; }
.codicon-globe:before { content: '\eb01'; }
.codicon-grabber:before { content: '\eb02'; }
.codicon-graph:before { content: '\eb03'; }
.codicon-gripper:before { content: '\eb04'; }
.codicon-heart:before { content: '\eb05'; }
.codicon-home:before { content: '\eb06'; }
.codicon-horizontal-rule:before { content: '\eb07'; }
.codicon-hubot:before { content: '\eb08'; }
.codicon-inbox:before { content: '\eb09'; }
.codicon-issue-reopened:before { content: '\eb0b'; }
.codicon-issues:before { content: '\eb0c'; }
.codicon-italic:before { content: '\eb0d'; }
.codicon-jersey:before { content: '\eb0e'; }
.codicon-json:before { content: '\eb0f'; }
.codicon-kebab-vertical:before { content: '\eb10'; }
.codicon-key:before { content: '\eb11'; }
.codicon-law:before { content: '\eb12'; }
.codicon-lightbulb-autofix:before { content: '\eb13'; }
.codicon-link-external:before { content: '\eb14'; }
.codicon-link:before { content: '\eb15'; }
.codicon-list-ordered:before { content: '\eb16'; }
.codicon-list-unordered:before { content: '\eb17'; }
.codicon-live-share:before { content: '\eb18'; }
.codicon-loading:before { content: '\eb19'; }
.codicon-location:before { content: '\eb1a'; }
.codicon-mail-read:before { content: '\eb1b'; }
.codicon-mail:before { content: '\eb1c'; }
.codicon-markdown:before { content: '\eb1d'; }
.codicon-megaphone:before { content: '\eb1e'; }
.codicon-mention:before { content: '\eb1f'; }
.codicon-milestone:before { content: '\eb20'; }
.codicon-git-pull-request-milestone:before { content: '\eb20'; }
.codicon-mortar-board:before { content: '\eb21'; }
.codicon-move:before { content: '\eb22'; }
.codicon-multiple-windows:before { content: '\eb23'; }
.codicon-mute:before { content: '\eb24'; }
.codicon-no-newline:before { content: '\eb25'; }
.codicon-note:before { content: '\eb26'; }
.codicon-octoface:before { content: '\eb27'; }
.codicon-open-preview:before { content: '\eb28'; }
.codicon-package:before { content: '\eb29'; }
.codicon-paintcan:before { content: '\eb2a'; }
.codicon-pin:before { content: '\eb2b'; }
.codicon-play:before { content: '\eb2c'; }
.codicon-run:before { content: '\eb2c'; }
.codicon-plug:before { content: '\eb2d'; }
.codicon-preserve-case:before { content: '\eb2e'; }
.codicon-preview:before { content: '\eb2f'; }
.codicon-project:before { content: '\eb30'; }
.codicon-pulse:before { content: '\eb31'; }
.codicon-question:before { content: '\eb32'; }
.codicon-quote:before { content: '\eb33'; }
.codicon-radio-tower:before { content: '\eb34'; }
.codicon-reactions:before { content: '\eb35'; }
.codicon-references:before { content: '\eb36'; }
.codicon-refresh:before { content: '\eb37'; }
.codicon-regex:before { content: '\eb38'; }
.codicon-remote-explorer:before { content: '\eb39'; }
.codicon-remote:before { content: '\eb3a'; }
.codicon-remove:before { content: '\eb3b'; }
.codicon-replace-all:before { content: '\eb3c'; }
.codicon-replace:before { content: '\eb3d'; }
.codicon-repo-clone:before { content: '\eb3e'; }
.codicon-repo-force-push:before { content: '\eb3f'; }
.codicon-repo-pull:before { content: '\eb40'; }
.codicon-repo-push:before { content: '\eb41'; }
.codicon-report:before { content: '\eb42'; }
.codicon-request-changes:before { content: '\eb43'; }
.codicon-rocket:before { content: '\eb44'; }
.codicon-root-folder-opened:before { content: '\eb45'; }
.codicon-root-folder:before { content: '\eb46'; }
.codicon-rss:before { content: '\eb47'; }
.codicon-ruby:before { content: '\eb48'; }
.codicon-save-all:before { content: '\eb49'; }
.codicon-save-as:before { content: '\eb4a'; }
.codicon-save:before { content: '\eb4b'; }
.codicon-screen-full:before { content: '\eb4c'; }
.codicon-screen-normal:before { content: '\eb4d'; }
.codicon-search-stop:before { content: '\eb4e'; }
.codicon-server:before { content: '\eb50'; }
.codicon-settings-gear:before { content: '\eb51'; }
.codicon-settings:before { content: '\eb52'; }
.codicon-shield:before { content: '\eb53'; }
.codicon-smiley:before { content: '\eb54'; }
.codicon-sort-precedence:before { content: '\eb55'; }
.codicon-split-horizontal:before { content: '\eb56'; }
.codicon-split-vertical:before { content: '\eb57'; }
.codicon-squirrel:before { content: '\eb58'; }
.codicon-star-full:before { content: '\eb59'; }
.codicon-star-half:before { content: '\eb5a'; }
.codicon-symbol-class:before { content: '\eb5b'; }
.codicon-symbol-color:before { content: '\eb5c'; }
.codicon-symbol-constant:before { content: '\eb5d'; }
.codicon-symbol-enum-member:before { content: '\eb5e'; }
.codicon-symbol-field:before { content: '\eb5f'; }
.codicon-symbol-file:before { content: '\eb60'; }
.codicon-symbol-interface:before { content: '\eb61'; }
.codicon-symbol-keyword:before { content: '\eb62'; }
.codicon-symbol-misc:before { content: '\eb63'; }
.codicon-symbol-operator:before { content: '\eb64'; }
.codicon-symbol-property:before { content: '\eb65'; }
.codicon-wrench:before { content: '\eb65'; }
.codicon-wrench-subaction:before { content: '\eb65'; }
.codicon-symbol-snippet:before { content: '\eb66'; }
.codicon-tasklist:before { content: '\eb67'; }
.codicon-telescope:before { content: '\eb68'; }
.codicon-text-size:before { content: '\eb69'; }
.codicon-three-bars:before { content: '\eb6a'; }
.codicon-thumbsdown:before { content: '\eb6b'; }
.codicon-thumbsup:before { content: '\eb6c'; }
.codicon-tools:before { content: '\eb6d'; }
.codicon-triangle-down:before { content: '\eb6e'; }
.codicon-triangle-left:before { content: '\eb6f'; }
.codicon-triangle-right:before { content: '\eb70'; }
.codicon-triangle-up:before { content: '\eb71'; }
.codicon-twitter:before { content: '\eb72'; }
.codicon-unfold:before { content: '\eb73'; }
.codicon-unlock:before { content: '\eb74'; }
.codicon-unmute:before { content: '\eb75'; }
.codicon-unverified:before { content: '\eb76'; }
.codicon-verified:before { content: '\eb77'; }
.codicon-versions:before { content: '\eb78'; }
.codicon-vm-active:before { content: '\eb79'; }
.codicon-vm-outline:before { content: '\eb7a'; }
.codicon-vm-running:before { content: '\eb7b'; }
.codicon-watch:before { content: '\eb7c'; }
.codicon-whitespace:before { content: '\eb7d'; }
.codicon-whole-word:before { content: '\eb7e'; }
.codicon-window:before { content: '\eb7f'; }
.codicon-word-wrap:before { content: '\eb80'; }
.codicon-zoom-in:before { content: '\eb81'; }
.codicon-zoom-out:before { content: '\eb82'; }
.codicon-list-filter:before { content: '\eb83'; }
.codicon-list-flat:before { content: '\eb84'; }
.codicon-list-selection:before { content: '\eb85'; }
.codicon-selection:before { content: '\eb85'; }
.codicon-list-tree:before { content: '\eb86'; }
.codicon-debug-breakpoint-function-unverified:before { content: '\eb87'; }
.codicon-debug-breakpoint-function:before { content: '\eb88'; }
.codicon-debug-breakpoint-function-disabled:before { content: '\eb88'; }
.codicon-debug-stackframe-active:before { content: '\eb89'; }
.codicon-circle-small-filled:before { content: '\eb8a'; }
.codicon-debug-stackframe-dot:before { content: '\eb8a'; }
.codicon-terminal-decoration-mark:before { content: '\eb8a'; }
.codicon-debug-stackframe:before { content: '\eb8b'; }
.codicon-debug-stackframe-focused:before { content: '\eb8b'; }
.codicon-debug-breakpoint-unsupported:before { content: '\eb8c'; }
.codicon-symbol-string:before { content: '\eb8d'; }
.codicon-debug-reverse-continue:before { content: '\eb8e'; }
.codicon-debug-step-back:before { content: '\eb8f'; }
.codicon-debug-restart-frame:before { content: '\eb90'; }
.codicon-debug-alt:before { content: '\eb91'; }
.codicon-call-incoming:before { content: '\eb92'; }
.codicon-call-outgoing:before { content: '\eb93'; }
.codicon-menu:before { content: '\eb94'; }
.codicon-expand-all:before { content: '\eb95'; }
.codicon-feedback:before { content: '\eb96'; }
.codicon-git-pull-request-reviewer:before { content: '\eb96'; }
.codicon-group-by-ref-type:before { content: '\eb97'; }
.codicon-ungroup-by-ref-type:before { content: '\eb98'; }
.codicon-account:before { content: '\eb99'; }
.codicon-git-pull-request-assignee:before { content: '\eb99'; }
.codicon-bell-dot:before { content: '\eb9a'; }
.codicon-debug-console:before { content: '\eb9b'; }
.codicon-library:before { content: '\eb9c'; }
.codicon-output:before { content: '\eb9d'; }
.codicon-run-all:before { content: '\eb9e'; }
.codicon-sync-ignored:before { content: '\eb9f'; }
.codicon-pinned:before { content: '\eba0'; }
.codicon-github-inverted:before { content: '\eba1'; }
.codicon-server-process:before { content: '\eba2'; }
.codicon-server-environment:before { content: '\eba3'; }
.codicon-pass:before { content: '\eba4'; }
.codicon-issue-closed:before { content: '\eba4'; }
.codicon-stop-circle:before { content: '\eba5'; }
.codicon-play-circle:before { content: '\eba6'; }
.codicon-record:before { content: '\eba7'; }
.codicon-debug-alt-small:before { content: '\eba8'; }
.codicon-vm-connect:before { content: '\eba9'; }
.codicon-cloud:before { content: '\ebaa'; }
.codicon-merge:before { content: '\ebab'; }
.codicon-export:before { content: '\ebac'; }
.codicon-graph-left:before { content: '\ebad'; }
.codicon-magnet:before { content: '\ebae'; }
.codicon-notebook:before { content: '\ebaf'; }
.codicon-redo:before { content: '\ebb0'; }
.codicon-check-all:before { content: '\ebb1'; }
.codicon-pinned-dirty:before { content: '\ebb2'; }
.codicon-pass-filled:before { content: '\ebb3'; }
.codicon-circle-large-filled:before { content: '\ebb4'; }
.codicon-circle-large:before { content: '\ebb5'; }
.codicon-circle-large-outline:before { content: '\ebb5'; }
.codicon-combine:before { content: '\ebb6'; }
.codicon-gather:before { content: '\ebb6'; }
.codicon-table:before { content: '\ebb7'; }
.codicon-variable-group:before { content: '\ebb8'; }
.codicon-type-hierarchy:before { content: '\ebb9'; }
.codicon-type-hierarchy-sub:before { content: '\ebba'; }
.codicon-type-hierarchy-super:before { content: '\ebbb'; }
.codicon-git-pull-request-create:before { content: '\ebbc'; }
.codicon-run-above:before { content: '\ebbd'; }
.codicon-run-below:before { content: '\ebbe'; }
.codicon-notebook-template:before { content: '\ebbf'; }
.codicon-debug-rerun:before { content: '\ebc0'; }
.codicon-workspace-trusted:before { content: '\ebc1'; }
.codicon-workspace-untrusted:before { content: '\ebc2'; }
.codicon-workspace-unknown:before { content: '\ebc3'; }
.codicon-terminal-cmd:before { content: '\ebc4'; }
.codicon-terminal-debian:before { content: '\ebc5'; }
.codicon-terminal-linux:before { content: '\ebc6'; }
.codicon-terminal-powershell:before { content: '\ebc7'; }
.codicon-terminal-tmux:before { content: '\ebc8'; }
.codicon-terminal-ubuntu:before { content: '\ebc9'; }
.codicon-terminal-bash:before { content: '\ebca'; }
.codicon-arrow-swap:before { content: '\ebcb'; }
.codicon-copy:before { content: '\ebcc'; }
.codicon-person-add:before { content: '\ebcd'; }
.codicon-filter-filled:before { content: '\ebce'; }
.codicon-wand:before { content: '\ebcf'; }
.codicon-debug-line-by-line:before { content: '\ebd0'; }
.codicon-inspect:before { content: '\ebd1'; }
.codicon-layers:before { content: '\ebd2'; }
.codicon-layers-dot:before { content: '\ebd3'; }
.codicon-layers-active:before { content: '\ebd4'; }
.codicon-compass:before { content: '\ebd5'; }
.codicon-compass-dot:before { content: '\ebd6'; }
.codicon-compass-active:before { content: '\ebd7'; }
.codicon-azure:before { content: '\ebd8'; }
.codicon-issue-draft:before { content: '\ebd9'; }
.codicon-git-pull-request-closed:before { content: '\ebda'; }
.codicon-git-pull-request-draft:before { content: '\ebdb'; }
.codicon-debug-all:before { content: '\ebdc'; }
.codicon-debug-coverage:before { content: '\ebdd'; }
.codicon-run-errors:before { content: '\ebde'; }
.codicon-folder-library:before { content: '\ebdf'; }
.codicon-debug-continue-small:before { content: '\ebe0'; }
.codicon-beaker-stop:before { content: '\ebe1'; }
.codicon-graph-line:before { content: '\ebe2'; }
.codicon-graph-scatter:before { content: '\ebe3'; }
.codicon-pie-chart:before { content: '\ebe4'; }
.codicon-bracket:before { content: '\eb0f'; }
.codicon-bracket-dot:before { content: '\ebe5'; }
.codicon-bracket-error:before { content: '\ebe6'; }
.codicon-lock-small:before { content: '\ebe7'; }
.codicon-azure-devops:before { content: '\ebe8'; }
.codicon-verified-filled:before { content: '\ebe9'; }
.codicon-newline:before { content: '\ebea'; }
.codicon-layout:before { content: '\ebeb'; }
.codicon-layout-activitybar-left:before { content: '\ebec'; }
.codicon-layout-activitybar-right:before { content: '\ebed'; }
.codicon-layout-panel-left:before { content: '\ebee'; }
.codicon-layout-panel-center:before { content: '\ebef'; }
.codicon-layout-panel-justify:before { content: '\ebf0'; }
.codicon-layout-panel-right:before { content: '\ebf1'; }
.codicon-layout-panel:before { content: '\ebf2'; }
.codicon-layout-sidebar-left:before { content: '\ebf3'; }
.codicon-layout-sidebar-right:before { content: '\ebf4'; }
.codicon-layout-statusbar:before { content: '\ebf5'; }
.codicon-layout-menubar:before { content: '\ebf6'; }
.codicon-layout-centered:before { content: '\ebf7'; }
.codicon-target:before { content: '\ebf8'; }
.codicon-indent:before { content: '\ebf9'; }
.codicon-record-small:before { content: '\ebfa'; }
.codicon-error-small:before { content: '\ebfb'; }
.codicon-terminal-decoration-error:before { content: '\ebfb'; }
.codicon-arrow-circle-down:before { content: '\ebfc'; }
.codicon-arrow-circle-left:before { content: '\ebfd'; }
.codicon-arrow-circle-right:before { content: '\ebfe'; }
.codicon-arrow-circle-up:before { content: '\ebff'; }
.codicon-layout-sidebar-right-off:before { content: '\ec00'; }
.codicon-layout-panel-off:before { content: '\ec01'; }
.codicon-layout-sidebar-left-off:before { content: '\ec02'; }
.codicon-blank:before { content: '\ec03'; }
.codicon-heart-filled:before { content: '\ec04'; }
.codicon-map:before { content: '\ec05'; }
.codicon-map-horizontal:before { content: '\ec05'; }
.codicon-fold-horizontal:before { content: '\ec05'; }
.codicon-map-filled:before { content: '\ec06'; }
.codicon-map-horizontal-filled:before { content: '\ec06'; }
.codicon-fold-horizontal-filled:before { content: '\ec06'; }
.codicon-circle-small:before { content: '\ec07'; }
.codicon-bell-slash:before { content: '\ec08'; }
.codicon-bell-slash-dot:before { content: '\ec09'; }
.codicon-comment-unresolved:before { content: '\ec0a'; }
.codicon-git-pull-request-go-to-changes:before { content: '\ec0b'; }
.codicon-git-pull-request-new-changes:before { content: '\ec0c'; }
.codicon-search-fuzzy:before { content: '\ec0d'; }
.codicon-comment-draft:before { content: '\ec0e'; }
.codicon-send:before { content: '\ec0f'; }
.codicon-sparkle:before { content: '\ec10'; }
.codicon-insert:before { content: '\ec11'; }
.codicon-mic:before { content: '\ec12'; }
.codicon-thumbsdown-filled:before { content: '\ec13'; }
.codicon-thumbsup-filled:before { content: '\ec14'; }
.codicon-coffee:before { content: '\ec15'; }
.codicon-snake:before { content: '\ec16'; }
.codicon-game:before { content: '\ec17'; }
.codicon-vr:before { content: '\ec18'; }
.codicon-chip:before { content: '\ec19'; }
.codicon-piano:before { content: '\ec1a'; }
.codicon-music:before { content: '\ec1b'; }
.codicon-mic-filled:before { content: '\ec1c'; }
.codicon-repo-fetch:before { content: '\ec1d'; }
.codicon-copilot:before { content: '\ec1e'; }
.codicon-lightbulb-sparkle:before { content: '\ec1f'; }
.codicon-robot:before { content: '\ec20'; }
.codicon-sparkle-filled:before { content: '\ec21'; }
.codicon-diff-single:before { content: '\ec22'; }
.codicon-diff-multiple:before { content: '\ec23'; }
.codicon-surround-with:before { content: '\ec24'; }
.codicon-share:before { content: '\ec25'; }
.codicon-git-stash:before { content: '\ec26'; }
.codicon-git-stash-apply:before { content: '\ec27'; }
.codicon-git-stash-pop:before { content: '\ec28'; }
.codicon-vscode:before { content: '\ec29'; }
.codicon-vscode-insiders:before { content: '\ec2a'; }
.codicon-code-oss:before { content: '\ec2b'; }
.codicon-run-coverage:before { content: '\ec2c'; }
.codicon-run-all-coverage:before { content: '\ec2d'; }
.codicon-coverage:before { content: '\ec2e'; }
.codicon-github-project:before { content: '\ec2f'; }
.codicon-map-vertical:before { content: '\ec30'; }
.codicon-fold-vertical:before { content: '\ec30'; }
.codicon-map-vertical-filled:before { content: '\ec31'; }
.codicon-fold-vertical-filled:before { content: '\ec31'; }
.codicon-go-to-search:before { content: '\ec32'; }
.codicon-percentage:before { content: '\ec33'; }
.codicon-sort-percentage:before { content: '\ec33'; }
.codicon-attach:before { content: '\ec34'; }
.codicon-dialog-error:before { content: '\ea87'; }
.codicon-dialog-warning:before { content: '\ea6c'; }
.codicon-dialog-info:before { content: '\ea74'; }
.codicon-dialog-close:before { content: '\ea76'; }
.codicon-tree-item-expanded:before { content: '\eab4'; }
.codicon-tree-filter-on-type-on:before { content: '\eb83'; }
.codicon-tree-filter-on-type-off:before { content: '\eb85'; }
.codicon-tree-filter-clear:before { content: '\ea76'; }
.codicon-tree-item-loading:before { content: '\eb19'; }
.codicon-menu-selection:before { content: '\eab2'; }
.codicon-menu-submenu:before { content: '\eab6'; }
.codicon-menubar-more:before { content: '\ea7c'; }
.codicon-scrollbar-button-left:before { content: '\eb6f'; }
.codicon-scrollbar-button-right:before { content: '\eb70'; }
.codicon-scrollbar-button-up:before { content: '\eb71'; }
.codicon-scrollbar-button-down:before { content: '\eb6e'; }
.codicon-toolbar-more:before { content: '\ea7c'; }
.codicon-quick-input-back:before { content: '\ea9b'; }
.codicon-drop-down-button:before { content: '\eab4'; }
.codicon-symbol-customcolor:before { content: '\eb5c'; }
.codicon-workspace-unspecified:before { content: '\ebc3'; }
.codicon-git-fetch:before { content: '\ec1d'; }
.codicon-lightbulb-sparkle-autofix:before { content: '\ec1f'; }
.codicon-debug-breakpoint-pending:before { content: '\ebd9'; }
.codicon-widget-close:before { content: '\ea76'; }
.codicon-goto-previous-location:before { content: '\eaa1'; }
.codicon-goto-next-location:before { content: '\ea9a'; }
.codicon-diff-review-insert:before { content: '\ea60'; }
.codicon-diff-review-remove:before { content: '\eb3b'; }
.codicon-diff-review-close:before { content: '\ea76'; }
.codicon-diff-insert:before { content: '\ea60'; }
.codicon-diff-remove:before { content: '\eb3b'; }
.codicon-gutter-lightbulb:before { content: '\ea61'; }
.codicon-gutter-lightbulb-auto-fix:before { content: '\eb13'; }
.codicon-gutter-lightbulb-sparkle:before { content: '\ec1f'; }
.codicon-gutter-lightbulb-aifix-auto-fix:before { content: '\ec1f'; }
.codicon-gutter-lightbulb-sparkle-filled:before { content: '\ec21'; }
.codicon-inline-suggestion-hints-next:before { content: '\eab6'; }
.codicon-inline-suggestion-hints-previous:before { content: '\eab5'; }
.codicon-hover-increase-verbosity:before { content: '\ea60'; }
.codicon-hover-decrease-verbosity:before { content: '\eb3b'; }
.codicon-find-collapsed:before { content: '\eab6'; }
.codicon-find-expanded:before { content: '\eab4'; }
.codicon-find-selection:before { content: '\eb85'; }
.codicon-find-replace:before { content: '\eb3d'; }
.codicon-find-replace-all:before { content: '\eb3c'; }
.codicon-find-previous-match:before { content: '\eaa1'; }
.codicon-find-next-match:before { content: '\ea9a'; }
.codicon-folding-expanded:before { content: '\eab4'; }
.codicon-folding-collapsed:before { content: '\eab6'; }
.codicon-folding-manual-collapsed:before { content: '\eab6'; }
.codicon-folding-manual-expanded:before { content: '\eab4'; }
.codicon-suggest-more-info:before { content: '\eab6'; }
.codicon-marker-navigation-next:before { content: '\ea9a'; }
.codicon-marker-navigation-previous:before { content: '\eaa1'; }
.codicon-parameter-hints-next:before { content: '\eab4'; }
.codicon-parameter-hints-previous:before { content: '\eab7'; }
.codicon-extensions-warning-message:before { content: '\ea6c'; }
:root { --vscode-icon-add-content: '\ea60'; --vscode-icon-add-font-family: 'codicon'; --vscode-icon-plus-content: '\ea60'; --vscode-icon-plus-font-family: 'codicon'; --vscode-icon-gist-new-content: '\ea60'; --vscode-icon-gist-new-font-family: 'codicon'; --vscode-icon-repo-create-content: '\ea60'; --vscode-icon-repo-create-font-family: 'codicon'; --vscode-icon-lightbulb-content: '\ea61'; --vscode-icon-lightbulb-font-family: 'codicon'; --vscode-icon-light-bulb-content: '\ea61'; --vscode-icon-light-bulb-font-family: 'codicon'; --vscode-icon-repo-content: '\ea62'; --vscode-icon-repo-font-family: 'codicon'; --vscode-icon-repo-delete-content: '\ea62'; --vscode-icon-repo-delete-font-family: 'codicon'; --vscode-icon-gist-fork-content: '\ea63'; --vscode-icon-gist-fork-font-family: 'codicon'; --vscode-icon-repo-forked-content: '\ea63'; --vscode-icon-repo-forked-font-family: 'codicon'; --vscode-icon-git-pull-request-content: '\ea64'; --vscode-icon-git-pull-request-font-family: 'codicon'; --vscode-icon-git-pull-request-abandoned-content: '\ea64'; --vscode-icon-git-pull-request-abandoned-font-family: 'codicon'; --vscode-icon-record-keys-content: '\ea65'; --vscode-icon-record-keys-font-family: 'codicon'; --vscode-icon-keyboard-content: '\ea65'; --vscode-icon-keyboard-font-family: 'codicon'; --vscode-icon-tag-content: '\ea66'; --vscode-icon-tag-font-family: 'codicon'; --vscode-icon-git-pull-request-label-content: '\ea66'; --vscode-icon-git-pull-request-label-font-family: 'codicon'; --vscode-icon-tag-add-content: '\ea66'; --vscode-icon-tag-add-font-family: 'codicon'; --vscode-icon-tag-remove-content: '\ea66'; --vscode-icon-tag-remove-font-family: 'codicon'; --vscode-icon-person-content: '\ea67'; --vscode-icon-person-font-family: 'codicon'; --vscode-icon-person-follow-content: '\ea67'; --vscode-icon-person-follow-font-family: 'codicon'; --vscode-icon-person-outline-content: '\ea67'; --vscode-icon-person-outline-font-family: 'codicon'; --vscode-icon-person-filled-content: '\ea67'; --vscode-icon-person-filled-font-family: 'codicon'; --vscode-icon-git-branch-content: '\ea68'; --vscode-icon-git-branch-font-family: 'codicon'; --vscode-icon-git-branch-create-content: '\ea68'; --vscode-icon-git-branch-create-font-family: 'codicon'; --vscode-icon-git-branch-delete-content: '\ea68'; --vscode-icon-git-branch-delete-font-family: 'codicon'; --vscode-icon-source-control-content: '\ea68'; --vscode-icon-source-control-font-family: 'codicon'; --vscode-icon-mirror-content: '\ea69'; --vscode-icon-mirror-font-family: 'codicon'; --vscode-icon-mirror-public-content: '\ea69'; --vscode-icon-mirror-public-font-family: 'codicon'; --vscode-icon-star-content: '\ea6a'; --vscode-icon-star-font-family: 'codicon'; --vscode-icon-star-add-content: '\ea6a'; --vscode-icon-star-add-font-family: 'codicon'; --vscode-icon-star-delete-content: '\ea6a'; --vscode-icon-star-delete-font-family: 'codicon'; --vscode-icon-star-empty-content: '\ea6a'; --vscode-icon-star-empty-font-family: 'codicon'; --vscode-icon-comment-content: '\ea6b'; --vscode-icon-comment-font-family: 'codicon'; --vscode-icon-comment-add-content: '\ea6b'; --vscode-icon-comment-add-font-family: 'codicon'; --vscode-icon-alert-content: '\ea6c'; --vscode-icon-alert-font-family: 'codicon'; --vscode-icon-warning-content: '\ea6c'; --vscode-icon-warning-font-family: 'codicon'; --vscode-icon-search-content: '\ea6d'; --vscode-icon-search-font-family: 'codicon'; --vscode-icon-search-save-content: '\ea6d'; --vscode-icon-search-save-font-family: 'codicon'; --vscode-icon-log-out-content: '\ea6e'; --vscode-icon-log-out-font-family: 'codicon'; --vscode-icon-sign-out-content: '\ea6e'; --vscode-icon-sign-out-font-family: 'codicon'; --vscode-icon-log-in-content: '\ea6f'; --vscode-icon-log-in-font-family: 'codicon'; --vscode-icon-sign-in-content: '\ea6f'; --vscode-icon-sign-in-font-family: 'codicon'; --vscode-icon-eye-content: '\ea70'; --vscode-icon-eye-font-family: 'codicon'; --vscode-icon-eye-unwatch-content: '\ea70'; --vscode-icon-eye-unwatch-font-family: 'codicon'; --vscode-icon-eye-watch-content: '\ea70'; --vscode-icon-eye-watch-font-family: 'codicon'; --vscode-icon-circle-filled-content: '\ea71'; --vscode-icon-circle-filled-font-family: 'codicon'; --vscode-icon-primitive-dot-content: '\ea71'; --vscode-icon-primitive-dot-font-family: 'codicon'; --vscode-icon-close-dirty-content: '\ea71'; --vscode-icon-close-dirty-font-family: 'codicon'; --vscode-icon-debug-breakpoint-content: '\ea71'; --vscode-icon-debug-breakpoint-font-family: 'codicon'; --vscode-icon-debug-breakpoint-disabled-content: '\ea71'; --vscode-icon-debug-breakpoint-disabled-font-family: 'codicon'; --vscode-icon-debug-hint-content: '\ea71'; --vscode-icon-debug-hint-font-family: 'codicon'; --vscode-icon-terminal-decoration-success-content: '\ea71'; --vscode-icon-terminal-decoration-success-font-family: 'codicon'; --vscode-icon-primitive-square-content: '\ea72'; --vscode-icon-primitive-square-font-family: 'codicon'; --vscode-icon-edit-content: '\ea73'; --vscode-icon-edit-font-family: 'codicon'; --vscode-icon-pencil-content: '\ea73'; --vscode-icon-pencil-font-family: 'codicon'; --vscode-icon-info-content: '\ea74'; --vscode-icon-info-font-family: 'codicon'; --vscode-icon-issue-opened-content: '\ea74'; --vscode-icon-issue-opened-font-family: 'codicon'; --vscode-icon-gist-private-content: '\ea75'; --vscode-icon-gist-private-font-family: 'codicon'; --vscode-icon-git-fork-private-content: '\ea75'; --vscode-icon-git-fork-private-font-family: 'codicon'; --vscode-icon-lock-content: '\ea75'; --vscode-icon-lock-font-family: 'codicon'; --vscode-icon-mirror-private-content: '\ea75'; --vscode-icon-mirror-private-font-family: 'codicon'; --vscode-icon-close-content: '\ea76'; --vscode-icon-close-font-family: 'codicon'; --vscode-icon-remove-close-content: '\ea76'; --vscode-icon-remove-close-font-family: 'codicon'; --vscode-icon-x-content: '\ea76'; --vscode-icon-x-font-family: 'codicon'; --vscode-icon-repo-sync-content: '\ea77'; --vscode-icon-repo-sync-font-family: 'codicon'; --vscode-icon-sync-content: '\ea77'; --vscode-icon-sync-font-family: 'codicon'; --vscode-icon-clone-content: '\ea78'; --vscode-icon-clone-font-family: 'codicon'; --vscode-icon-desktop-download-content: '\ea78'; --vscode-icon-desktop-download-font-family: 'codicon'; --vscode-icon-beaker-content: '\ea79'; --vscode-icon-beaker-font-family: 'codicon'; --vscode-icon-microscope-content: '\ea79'; --vscode-icon-microscope-font-family: 'codicon'; --vscode-icon-vm-content: '\ea7a'; --vscode-icon-vm-font-family: 'codicon'; --vscode-icon-device-desktop-content: '\ea7a'; --vscode-icon-device-desktop-font-family: 'codicon'; --vscode-icon-file-content: '\ea7b'; --vscode-icon-file-font-family: 'codicon'; --vscode-icon-file-text-content: '\ea7b'; --vscode-icon-file-text-font-family: 'codicon'; --vscode-icon-more-content: '\ea7c'; --vscode-icon-more-font-family: 'codicon'; --vscode-icon-ellipsis-content: '\ea7c'; --vscode-icon-ellipsis-font-family: 'codicon'; --vscode-icon-kebab-horizontal-content: '\ea7c'; --vscode-icon-kebab-horizontal-font-family: 'codicon'; --vscode-icon-mail-reply-content: '\ea7d'; --vscode-icon-mail-reply-font-family: 'codicon'; --vscode-icon-reply-content: '\ea7d'; --vscode-icon-reply-font-family: 'codicon'; --vscode-icon-organization-content: '\ea7e'; --vscode-icon-organization-font-family: 'codicon'; --vscode-icon-organization-filled-content: '\ea7e'; --vscode-icon-organization-filled-font-family: 'codicon'; --vscode-icon-organization-outline-content: '\ea7e'; --vscode-icon-organization-outline-font-family: 'codicon'; --vscode-icon-new-file-content: '\ea7f'; --vscode-icon-new-file-font-family: 'codicon'; --vscode-icon-file-add-content: '\ea7f'; --vscode-icon-file-add-font-family: 'codicon'; --vscode-icon-new-folder-content: '\ea80'; --vscode-icon-new-folder-font-family: 'codicon'; --vscode-icon-file-directory-create-content: '\ea80'; --vscode-icon-file-directory-create-font-family: 'codicon'; --vscode-icon-trash-content: '\ea81'; --vscode-icon-trash-font-family: 'codicon'; --vscode-icon-trashcan-content: '\ea81'; --vscode-icon-trashcan-font-family: 'codicon'; --vscode-icon-history-content: '\ea82'; --vscode-icon-history-font-family: 'codicon'; --vscode-icon-clock-content: '\ea82'; --vscode-icon-clock-font-family: 'codicon'; --vscode-icon-folder-content: '\ea83'; --vscode-icon-folder-font-family: 'codicon'; --vscode-icon-file-directory-content: '\ea83'; --vscode-icon-file-directory-font-family: 'codicon'; --vscode-icon-symbol-folder-content: '\ea83'; --vscode-icon-symbol-folder-font-family: 'codicon'; --vscode-icon-logo-github-content: '\ea84'; --vscode-icon-logo-github-font-family: 'codicon'; --vscode-icon-mark-github-content: '\ea84'; --vscode-icon-mark-github-font-family: 'codicon'; --vscode-icon-github-content: '\ea84'; --vscode-icon-github-font-family: 'codicon'; --vscode-icon-terminal-content: '\ea85'; --vscode-icon-terminal-font-family: 'codicon'; --vscode-icon-console-content: '\ea85'; --vscode-icon-console-font-family: 'codicon'; --vscode-icon-repl-content: '\ea85'; --vscode-icon-repl-font-family: 'codicon'; --vscode-icon-zap-content: '\ea86'; --vscode-icon-zap-font-family: 'codicon'; --vscode-icon-symbol-event-content: '\ea86'; --vscode-icon-symbol-event-font-family: 'codicon'; --vscode-icon-error-content: '\ea87'; --vscode-icon-error-font-family: 'codicon'; --vscode-icon-stop-content: '\ea87'; --vscode-icon-stop-font-family: 'codicon'; --vscode-icon-variable-content: '\ea88'; --vscode-icon-variable-font-family: 'codicon'; --vscode-icon-symbol-variable-content: '\ea88'; --vscode-icon-symbol-variable-font-family: 'codicon'; --vscode-icon-array-content: '\ea8a'; --vscode-icon-array-font-family: 'codicon'; --vscode-icon-symbol-array-content: '\ea8a'; --vscode-icon-symbol-array-font-family: 'codicon'; --vscode-icon-symbol-module-content: '\ea8b'; --vscode-icon-symbol-module-font-family: 'codicon'; --vscode-icon-symbol-package-content: '\ea8b'; --vscode-icon-symbol-package-font-family: 'codicon'; --vscode-icon-symbol-namespace-content: '\ea8b'; --vscode-icon-symbol-namespace-font-family: 'codicon'; --vscode-icon-symbol-object-content: '\ea8b'; --vscode-icon-symbol-object-font-family: 'codicon'; --vscode-icon-symbol-method-content: '\ea8c'; --vscode-icon-symbol-method-font-family: 'codicon'; --vscode-icon-symbol-function-content: '\ea8c'; --vscode-icon-symbol-function-font-family: 'codicon'; --vscode-icon-symbol-constructor-content: '\ea8c'; --vscode-icon-symbol-constructor-font-family: 'codicon'; --vscode-icon-symbol-boolean-content: '\ea8f'; --vscode-icon-symbol-boolean-font-family: 'codicon'; --vscode-icon-symbol-null-content: '\ea8f'; --vscode-icon-symbol-null-font-family: 'codicon'; --vscode-icon-symbol-numeric-content: '\ea90'; --vscode-icon-symbol-numeric-font-family: 'codicon'; --vscode-icon-symbol-number-content: '\ea90'; --vscode-icon-symbol-number-font-family: 'codicon'; --vscode-icon-symbol-structure-content: '\ea91'; --vscode-icon-symbol-structure-font-family: 'codicon'; --vscode-icon-symbol-struct-content: '\ea91'; --vscode-icon-symbol-struct-font-family: 'codicon'; --vscode-icon-symbol-parameter-content: '\ea92'; --vscode-icon-symbol-parameter-font-family: 'codicon'; --vscode-icon-symbol-type-parameter-content: '\ea92'; --vscode-icon-symbol-type-parameter-font-family: 'codicon'; --vscode-icon-symbol-key-content: '\ea93'; --vscode-icon-symbol-key-font-family: 'codicon'; --vscode-icon-symbol-text-content: '\ea93'; --vscode-icon-symbol-text-font-family: 'codicon'; --vscode-icon-symbol-reference-content: '\ea94'; --vscode-icon-symbol-reference-font-family: 'codicon'; --vscode-icon-go-to-file-content: '\ea94'; --vscode-icon-go-to-file-font-family: 'codicon'; --vscode-icon-symbol-enum-content: '\ea95'; --vscode-icon-symbol-enum-font-family: 'codicon'; --vscode-icon-symbol-value-content: '\ea95'; --vscode-icon-symbol-value-font-family: 'codicon'; --vscode-icon-symbol-ruler-content: '\ea96'; --vscode-icon-symbol-ruler-font-family: 'codicon'; --vscode-icon-symbol-unit-content: '\ea96'; --vscode-icon-symbol-unit-font-family: 'codicon'; --vscode-icon-activate-breakpoints-content: '\ea97'; --vscode-icon-activate-breakpoints-font-family: 'codicon'; --vscode-icon-archive-content: '\ea98'; --vscode-icon-archive-font-family: 'codicon'; --vscode-icon-arrow-both-content: '\ea99'; --vscode-icon-arrow-both-font-family: 'codicon'; --vscode-icon-arrow-down-content: '\ea9a'; --vscode-icon-arrow-down-font-family: 'codicon'; --vscode-icon-arrow-left-content: '\ea9b'; --vscode-icon-arrow-left-font-family: 'codicon'; --vscode-icon-arrow-right-content: '\ea9c'; --vscode-icon-arrow-right-font-family: 'codicon'; --vscode-icon-arrow-small-down-content: '\ea9d'; --vscode-icon-arrow-small-down-font-family: 'codicon'; --vscode-icon-arrow-small-left-content: '\ea9e'; --vscode-icon-arrow-small-left-font-family: 'codicon'; --vscode-icon-arrow-small-right-content: '\ea9f'; --vscode-icon-arrow-small-right-font-family: 'codicon'; --vscode-icon-arrow-small-up-content: '\eaa0'; --vscode-icon-arrow-small-up-font-family: 'codicon'; --vscode-icon-arrow-up-content: '\eaa1'; --vscode-icon-arrow-up-font-family: 'codicon'; --vscode-icon-bell-content: '\eaa2'; --vscode-icon-bell-font-family: 'codicon'; --vscode-icon-bold-content: '\eaa3'; --vscode-icon-bold-font-family: 'codicon'; --vscode-icon-book-content: '\eaa4'; --vscode-icon-book-font-family: 'codicon'; --vscode-icon-bookmark-content: '\eaa5'; --vscode-icon-bookmark-font-family: 'codicon'; --vscode-icon-debug-breakpoint-conditional-unverified-content: '\eaa6'; --vscode-icon-debug-breakpoint-conditional-unverified-font-family: 'codicon'; --vscode-icon-debug-breakpoint-conditional-content: '\eaa7'; --vscode-icon-debug-breakpoint-conditional-font-family: 'codicon'; --vscode-icon-debug-breakpoint-conditional-disabled-content: '\eaa7'; --vscode-icon-debug-breakpoint-conditional-disabled-font-family: 'codicon'; --vscode-icon-debug-breakpoint-data-unverified-content: '\eaa8'; --vscode-icon-debug-breakpoint-data-unverified-font-family: 'codicon'; --vscode-icon-debug-breakpoint-data-content: '\eaa9'; --vscode-icon-debug-breakpoint-data-font-family: 'codicon'; --vscode-icon-debug-breakpoint-data-disabled-content: '\eaa9'; --vscode-icon-debug-breakpoint-data-disabled-font-family: 'codicon'; --vscode-icon-debug-breakpoint-log-unverified-content: '\eaaa'; --vscode-icon-debug-breakpoint-log-unverified-font-family: 'codicon'; --vscode-icon-debug-breakpoint-log-content: '\eaab'; --vscode-icon-debug-breakpoint-log-font-family: 'codicon'; --vscode-icon-debug-breakpoint-log-disabled-content: '\eaab'; --vscode-icon-debug-breakpoint-log-disabled-font-family: 'codicon'; --vscode-icon-briefcase-content: '\eaac'; --vscode-icon-briefcase-font-family: 'codicon'; --vscode-icon-broadcast-content: '\eaad'; --vscode-icon-broadcast-font-family: 'codicon'; --vscode-icon-browser-content: '\eaae'; --vscode-icon-browser-font-family: 'codicon'; --vscode-icon-bug-content: '\eaaf'; --vscode-icon-bug-font-family: 'codicon'; --vscode-icon-calendar-content: '\eab0'; --vscode-icon-calendar-font-family: 'codicon'; --vscode-icon-case-sensitive-content: '\eab1'; --vscode-icon-case-sensitive-font-family: 'codicon'; --vscode-icon-check-content: '\eab2'; --vscode-icon-check-font-family: 'codicon'; --vscode-icon-checklist-content: '\eab3'; --vscode-icon-checklist-font-family: 'codicon'; --vscode-icon-chevron-down-content: '\eab4'; --vscode-icon-chevron-down-font-family: 'codicon'; --vscode-icon-chevron-left-content: '\eab5'; --vscode-icon-chevron-left-font-family: 'codicon'; --vscode-icon-chevron-right-content: '\eab6'; --vscode-icon-chevron-right-font-family: 'codicon'; --vscode-icon-chevron-up-content: '\eab7'; --vscode-icon-chevron-up-font-family: 'codicon'; --vscode-icon-chrome-close-content: '\eab8'; --vscode-icon-chrome-close-font-family: 'codicon'; --vscode-icon-chrome-maximize-content: '\eab9'; --vscode-icon-chrome-maximize-font-family: 'codicon'; --vscode-icon-chrome-minimize-content: '\eaba'; --vscode-icon-chrome-minimize-font-family: 'codicon'; --vscode-icon-chrome-restore-content: '\eabb'; --vscode-icon-chrome-restore-font-family: 'codicon'; --vscode-icon-circle-outline-content: '\eabc'; --vscode-icon-circle-outline-font-family: 'codicon'; --vscode-icon-circle-content: '\eabc'; --vscode-icon-circle-font-family: 'codicon'; --vscode-icon-debug-breakpoint-unverified-content: '\eabc'; --vscode-icon-debug-breakpoint-unverified-font-family: 'codicon'; --vscode-icon-terminal-decoration-incomplete-content: '\eabc'; --vscode-icon-terminal-decoration-incomplete-font-family: 'codicon'; --vscode-icon-circle-slash-content: '\eabd'; --vscode-icon-circle-slash-font-family: 'codicon'; --vscode-icon-circuit-board-content: '\eabe'; --vscode-icon-circuit-board-font-family: 'codicon'; --vscode-icon-clear-all-content: '\eabf'; --vscode-icon-clear-all-font-family: 'codicon'; --vscode-icon-clippy-content: '\eac0'; --vscode-icon-clippy-font-family: 'codicon'; --vscode-icon-close-all-content: '\eac1'; --vscode-icon-close-all-font-family: 'codicon'; --vscode-icon-cloud-download-content: '\eac2'; --vscode-icon-cloud-download-font-family: 'codicon'; --vscode-icon-cloud-upload-content: '\eac3'; --vscode-icon-cloud-upload-font-family: 'codicon'; --vscode-icon-code-content: '\eac4'; --vscode-icon-code-font-family: 'codicon'; --vscode-icon-collapse-all-content: '\eac5'; --vscode-icon-collapse-all-font-family: 'codicon'; --vscode-icon-color-mode-content: '\eac6'; --vscode-icon-color-mode-font-family: 'codicon'; --vscode-icon-comment-discussion-content: '\eac7'; --vscode-icon-comment-discussion-font-family: 'codicon'; --vscode-icon-credit-card-content: '\eac9'; --vscode-icon-credit-card-font-family: 'codicon'; --vscode-icon-dash-content: '\eacc'; --vscode-icon-dash-font-family: 'codicon'; --vscode-icon-dashboard-content: '\eacd'; --vscode-icon-dashboard-font-family: 'codicon'; --vscode-icon-database-content: '\eace'; --vscode-icon-database-font-family: 'codicon'; --vscode-icon-debug-continue-content: '\eacf'; --vscode-icon-debug-continue-font-family: 'codicon'; --vscode-icon-debug-disconnect-content: '\ead0'; --vscode-icon-debug-disconnect-font-family: 'codicon'; --vscode-icon-debug-pause-content: '\ead1'; --vscode-icon-debug-pause-font-family: 'codicon'; --vscode-icon-debug-restart-content: '\ead2'; --vscode-icon-debug-restart-font-family: 'codicon'; --vscode-icon-debug-start-content: '\ead3'; --vscode-icon-debug-start-font-family: 'codicon'; --vscode-icon-debug-step-into-content: '\ead4'; --vscode-icon-debug-step-into-font-family: 'codicon'; --vscode-icon-debug-step-out-content: '\ead5'; --vscode-icon-debug-step-out-font-family: 'codicon'; --vscode-icon-debug-step-over-content: '\ead6'; --vscode-icon-debug-step-over-font-family: 'codicon'; --vscode-icon-debug-stop-content: '\ead7'; --vscode-icon-debug-stop-font-family: 'codicon'; --vscode-icon-debug-content: '\ead8'; --vscode-icon-debug-font-family: 'codicon'; --vscode-icon-device-camera-video-content: '\ead9'; --vscode-icon-device-camera-video-font-family: 'codicon'; --vscode-icon-device-camera-content: '\eada'; --vscode-icon-device-camera-font-family: 'codicon'; --vscode-icon-device-mobile-content: '\eadb'; --vscode-icon-device-mobile-font-family: 'codicon'; --vscode-icon-diff-added-content: '\eadc'; --vscode-icon-diff-added-font-family: 'codicon'; --vscode-icon-diff-ignored-content: '\eadd'; --vscode-icon-diff-ignored-font-family: 'codicon'; --vscode-icon-diff-modified-content: '\eade'; --vscode-icon-diff-modified-font-family: 'codicon'; --vscode-icon-diff-removed-content: '\eadf'; --vscode-icon-diff-removed-font-family: 'codicon'; --vscode-icon-diff-renamed-content: '\eae0'; --vscode-icon-diff-renamed-font-family: 'codicon'; --vscode-icon-diff-content: '\eae1'; --vscode-icon-diff-font-family: 'codicon'; --vscode-icon-diff-sidebyside-content: '\eae1'; --vscode-icon-diff-sidebyside-font-family: 'codicon'; --vscode-icon-discard-content: '\eae2'; --vscode-icon-discard-font-family: 'codicon'; --vscode-icon-editor-layout-content: '\eae3'; --vscode-icon-editor-layout-font-family: 'codicon'; --vscode-icon-empty-window-content: '\eae4'; --vscode-icon-empty-window-font-family: 'codicon'; --vscode-icon-exclude-content: '\eae5'; --vscode-icon-exclude-font-family: 'codicon'; --vscode-icon-extensions-content: '\eae6'; --vscode-icon-extensions-font-family: 'codicon'; --vscode-icon-eye-closed-content: '\eae7'; --vscode-icon-eye-closed-font-family: 'codicon'; --vscode-icon-file-binary-content: '\eae8'; --vscode-icon-file-binary-font-family: 'codicon'; --vscode-icon-file-code-content: '\eae9'; --vscode-icon-file-code-font-family: 'codicon'; --vscode-icon-file-media-content: '\eaea'; --vscode-icon-file-media-font-family: 'codicon'; --vscode-icon-file-pdf-content: '\eaeb'; --vscode-icon-file-pdf-font-family: 'codicon'; --vscode-icon-file-submodule-content: '\eaec'; --vscode-icon-file-submodule-font-family: 'codicon'; --vscode-icon-file-symlink-directory-content: '\eaed'; --vscode-icon-file-symlink-directory-font-family: 'codicon'; --vscode-icon-file-symlink-file-content: '\eaee'; --vscode-icon-file-symlink-file-font-family: 'codicon'; --vscode-icon-file-zip-content: '\eaef'; --vscode-icon-file-zip-font-family: 'codicon'; --vscode-icon-files-content: '\eaf0'; --vscode-icon-files-font-family: 'codicon'; --vscode-icon-filter-content: '\eaf1'; --vscode-icon-filter-font-family: 'codicon'; --vscode-icon-flame-content: '\eaf2'; --vscode-icon-flame-font-family: 'codicon'; --vscode-icon-fold-down-content: '\eaf3'; --vscode-icon-fold-down-font-family: 'codicon'; --vscode-icon-fold-up-content: '\eaf4'; --vscode-icon-fold-up-font-family: 'codicon'; --vscode-icon-fold-content: '\eaf5'; --vscode-icon-fold-font-family: 'codicon'; --vscode-icon-folder-active-content: '\eaf6'; --vscode-icon-folder-active-font-family: 'codicon'; --vscode-icon-folder-opened-content: '\eaf7'; --vscode-icon-folder-opened-font-family: 'codicon'; --vscode-icon-gear-content: '\eaf8'; --vscode-icon-gear-font-family: 'codicon'; --vscode-icon-gift-content: '\eaf9'; --vscode-icon-gift-font-family: 'codicon'; --vscode-icon-gist-secret-content: '\eafa'; --vscode-icon-gist-secret-font-family: 'codicon'; --vscode-icon-gist-content: '\eafb'; --vscode-icon-gist-font-family: 'codicon'; --vscode-icon-git-commit-content: '\eafc'; --vscode-icon-git-commit-font-family: 'codicon'; --vscode-icon-git-compare-content: '\eafd'; --vscode-icon-git-compare-font-family: 'codicon'; --vscode-icon-compare-changes-content: '\eafd'; --vscode-icon-compare-changes-font-family: 'codicon'; --vscode-icon-git-merge-content: '\eafe'; --vscode-icon-git-merge-font-family: 'codicon'; --vscode-icon-github-action-content: '\eaff'; --vscode-icon-github-action-font-family: 'codicon'; --vscode-icon-github-alt-content: '\eb00'; --vscode-icon-github-alt-font-family: 'codicon'; --vscode-icon-globe-content: '\eb01'; --vscode-icon-globe-font-family: 'codicon'; --vscode-icon-grabber-content: '\eb02'; --vscode-icon-grabber-font-family: 'codicon'; --vscode-icon-graph-content: '\eb03'; --vscode-icon-graph-font-family: 'codicon'; --vscode-icon-gripper-content: '\eb04'; --vscode-icon-gripper-font-family: 'codicon'; --vscode-icon-heart-content: '\eb05'; --vscode-icon-heart-font-family: 'codicon'; --vscode-icon-home-content: '\eb06'; --vscode-icon-home-font-family: 'codicon'; --vscode-icon-horizontal-rule-content: '\eb07'; --vscode-icon-horizontal-rule-font-family: 'codicon'; --vscode-icon-hubot-content: '\eb08'; --vscode-icon-hubot-font-family: 'codicon'; --vscode-icon-inbox-content: '\eb09'; --vscode-icon-inbox-font-family: 'codicon'; --vscode-icon-issue-reopened-content: '\eb0b'; --vscode-icon-issue-reopened-font-family: 'codicon'; --vscode-icon-issues-content: '\eb0c'; --vscode-icon-issues-font-family: 'codicon'; --vscode-icon-italic-content: '\eb0d'; --vscode-icon-italic-font-family: 'codicon'; --vscode-icon-jersey-content: '\eb0e'; --vscode-icon-jersey-font-family: 'codicon'; --vscode-icon-json-content: '\eb0f'; --vscode-icon-json-font-family: 'codicon'; --vscode-icon-kebab-vertical-content: '\eb10'; --vscode-icon-kebab-vertical-font-family: 'codicon'; --vscode-icon-key-content: '\eb11'; --vscode-icon-key-font-family: 'codicon'; --vscode-icon-law-content: '\eb12'; --vscode-icon-law-font-family: 'codicon'; --vscode-icon-lightbulb-autofix-content: '\eb13'; --vscode-icon-lightbulb-autofix-font-family: 'codicon'; --vscode-icon-link-external-content: '\eb14'; --vscode-icon-link-external-font-family: 'codicon'; --vscode-icon-link-content: '\eb15'; --vscode-icon-link-font-family: 'codicon'; --vscode-icon-list-ordered-content: '\eb16'; --vscode-icon-list-ordered-font-family: 'codicon'; --vscode-icon-list-unordered-content: '\eb17'; --vscode-icon-list-unordered-font-family: 'codicon'; --vscode-icon-live-share-content: '\eb18'; --vscode-icon-live-share-font-family: 'codicon'; --vscode-icon-loading-content: '\eb19'; --vscode-icon-loading-font-family: 'codicon'; --vscode-icon-location-content: '\eb1a'; --vscode-icon-location-font-family: 'codicon'; --vscode-icon-mail-read-content: '\eb1b'; --vscode-icon-mail-read-font-family: 'codicon'; --vscode-icon-mail-content: '\eb1c'; --vscode-icon-mail-font-family: 'codicon'; --vscode-icon-markdown-content: '\eb1d'; --vscode-icon-markdown-font-family: 'codicon'; --vscode-icon-megaphone-content: '\eb1e'; --vscode-icon-megaphone-font-family: 'codicon'; --vscode-icon-mention-content: '\eb1f'; --vscode-icon-mention-font-family: 'codicon'; --vscode-icon-milestone-content: '\eb20'; --vscode-icon-milestone-font-family: 'codicon'; --vscode-icon-git-pull-request-milestone-content: '\eb20'; --vscode-icon-git-pull-request-milestone-font-family: 'codicon'; --vscode-icon-mortar-board-content: '\eb21'; --vscode-icon-mortar-board-font-family: 'codicon'; --vscode-icon-move-content: '\eb22'; --vscode-icon-move-font-family: 'codicon'; --vscode-icon-multiple-windows-content: '\eb23'; --vscode-icon-multiple-windows-font-family: 'codicon'; --vscode-icon-mute-content: '\eb24'; --vscode-icon-mute-font-family: 'codicon'; --vscode-icon-no-newline-content: '\eb25'; --vscode-icon-no-newline-font-family: 'codicon'; --vscode-icon-note-content: '\eb26'; --vscode-icon-note-font-family: 'codicon'; --vscode-icon-octoface-content: '\eb27'; --vscode-icon-octoface-font-family: 'codicon'; --vscode-icon-open-preview-content: '\eb28'; --vscode-icon-open-preview-font-family: 'codicon'; --vscode-icon-package-content: '\eb29'; --vscode-icon-package-font-family: 'codicon'; --vscode-icon-paintcan-content: '\eb2a'; --vscode-icon-paintcan-font-family: 'codicon'; --vscode-icon-pin-content: '\eb2b'; --vscode-icon-pin-font-family: 'codicon'; --vscode-icon-play-content: '\eb2c'; --vscode-icon-play-font-family: 'codicon'; --vscode-icon-run-content: '\eb2c'; --vscode-icon-run-font-family: 'codicon'; --vscode-icon-plug-content: '\eb2d'; --vscode-icon-plug-font-family: 'codicon'; --vscode-icon-preserve-case-content: '\eb2e'; --vscode-icon-preserve-case-font-family: 'codicon'; --vscode-icon-preview-content: '\eb2f'; --vscode-icon-preview-font-family: 'codicon'; --vscode-icon-project-content: '\eb30'; --vscode-icon-project-font-family: 'codicon'; --vscode-icon-pulse-content: '\eb31'; --vscode-icon-pulse-font-family: 'codicon'; --vscode-icon-question-content: '\eb32'; --vscode-icon-question-font-family: 'codicon'; --vscode-icon-quote-content: '\eb33'; --vscode-icon-quote-font-family: 'codicon'; --vscode-icon-radio-tower-content: '\eb34'; --vscode-icon-radio-tower-font-family: 'codicon'; --vscode-icon-reactions-content: '\eb35'; --vscode-icon-reactions-font-family: 'codicon'; --vscode-icon-references-content: '\eb36'; --vscode-icon-references-font-family: 'codicon'; --vscode-icon-refresh-content: '\eb37'; --vscode-icon-refresh-font-family: 'codicon'; --vscode-icon-regex-content: '\eb38'; --vscode-icon-regex-font-family: 'codicon'; --vscode-icon-remote-explorer-content: '\eb39'; --vscode-icon-remote-explorer-font-family: 'codicon'; --vscode-icon-remote-content: '\eb3a'; --vscode-icon-remote-font-family: 'codicon'; --vscode-icon-remove-content: '\eb3b'; --vscode-icon-remove-font-family: 'codicon'; --vscode-icon-replace-all-content: '\eb3c'; --vscode-icon-replace-all-font-family: 'codicon'; --vscode-icon-replace-content: '\eb3d'; --vscode-icon-replace-font-family: 'codicon'; --vscode-icon-repo-clone-content: '\eb3e'; --vscode-icon-repo-clone-font-family: 'codicon'; --vscode-icon-repo-force-push-content: '\eb3f'; --vscode-icon-repo-force-push-font-family: 'codicon'; --vscode-icon-repo-pull-content: '\eb40'; --vscode-icon-repo-pull-font-family: 'codicon'; --vscode-icon-repo-push-content: '\eb41'; --vscode-icon-repo-push-font-family: 'codicon'; --vscode-icon-report-content: '\eb42'; --vscode-icon-report-font-family: 'codicon'; --vscode-icon-request-changes-content: '\eb43'; --vscode-icon-request-changes-font-family: 'codicon'; --vscode-icon-rocket-content: '\eb44'; --vscode-icon-rocket-font-family: 'codicon'; --vscode-icon-root-folder-opened-content: '\eb45'; --vscode-icon-root-folder-opened-font-family: 'codicon'; --vscode-icon-root-folder-content: '\eb46'; --vscode-icon-root-folder-font-family: 'codicon'; --vscode-icon-rss-content: '\eb47'; --vscode-icon-rss-font-family: 'codicon'; --vscode-icon-ruby-content: '\eb48'; --vscode-icon-ruby-font-family: 'codicon'; --vscode-icon-save-all-content: '\eb49'; --vscode-icon-save-all-font-family: 'codicon'; --vscode-icon-save-as-content: '\eb4a'; --vscode-icon-save-as-font-family: 'codicon'; --vscode-icon-save-content: '\eb4b'; --vscode-icon-save-font-family: 'codicon'; --vscode-icon-screen-full-content: '\eb4c'; --vscode-icon-screen-full-font-family: 'codicon'; --vscode-icon-screen-normal-content: '\eb4d'; --vscode-icon-screen-normal-font-family: 'codicon'; --vscode-icon-search-stop-content: '\eb4e'; --vscode-icon-search-stop-font-family: 'codicon'; --vscode-icon-server-content: '\eb50'; --vscode-icon-server-font-family: 'codicon'; --vscode-icon-settings-gear-content: '\eb51'; --vscode-icon-settings-gear-font-family: 'codicon'; --vscode-icon-settings-content: '\eb52'; --vscode-icon-settings-font-family: 'codicon'; --vscode-icon-shield-content: '\eb53'; --vscode-icon-shield-font-family: 'codicon'; --vscode-icon-smiley-content: '\eb54'; --vscode-icon-smiley-font-family: 'codicon'; --vscode-icon-sort-precedence-content: '\eb55'; --vscode-icon-sort-precedence-font-family: 'codicon'; --vscode-icon-split-horizontal-content: '\eb56'; --vscode-icon-split-horizontal-font-family: 'codicon'; --vscode-icon-split-vertical-content: '\eb57'; --vscode-icon-split-vertical-font-family: 'codicon'; --vscode-icon-squirrel-content: '\eb58'; --vscode-icon-squirrel-font-family: 'codicon'; --vscode-icon-star-full-content: '\eb59'; --vscode-icon-star-full-font-family: 'codicon'; --vscode-icon-star-half-content: '\eb5a'; --vscode-icon-star-half-font-family: 'codicon'; --vscode-icon-symbol-class-content: '\eb5b'; --vscode-icon-symbol-class-font-family: 'codicon'; --vscode-icon-symbol-color-content: '\eb5c'; --vscode-icon-symbol-color-font-family: 'codicon'; --vscode-icon-symbol-constant-content: '\eb5d'; --vscode-icon-symbol-constant-font-family: 'codicon'; --vscode-icon-symbol-enum-member-content: '\eb5e'; --vscode-icon-symbol-enum-member-font-family: 'codicon'; --vscode-icon-symbol-field-content: '\eb5f'; --vscode-icon-symbol-field-font-family: 'codicon'; --vscode-icon-symbol-file-content: '\eb60'; --vscode-icon-symbol-file-font-family: 'codicon'; --vscode-icon-symbol-interface-content: '\eb61'; --vscode-icon-symbol-interface-font-family: 'codicon'; --vscode-icon-symbol-keyword-content: '\eb62'; --vscode-icon-symbol-keyword-font-family: 'codicon'; --vscode-icon-symbol-misc-content: '\eb63'; --vscode-icon-symbol-misc-font-family: 'codicon'; --vscode-icon-symbol-operator-content: '\eb64'; --vscode-icon-symbol-operator-font-family: 'codicon'; --vscode-icon-symbol-property-content: '\eb65'; --vscode-icon-symbol-property-font-family: 'codicon'; --vscode-icon-wrench-content: '\eb65'; --vscode-icon-wrench-font-family: 'codicon'; --vscode-icon-wrench-subaction-content: '\eb65'; --vscode-icon-wrench-subaction-font-family: 'codicon'; --vscode-icon-symbol-snippet-content: '\eb66'; --vscode-icon-symbol-snippet-font-family: 'codicon'; --vscode-icon-tasklist-content: '\eb67'; --vscode-icon-tasklist-font-family: 'codicon'; --vscode-icon-telescope-content: '\eb68'; --vscode-icon-telescope-font-family: 'codicon'; --vscode-icon-text-size-content: '\eb69'; --vscode-icon-text-size-font-family: 'codicon'; --vscode-icon-three-bars-content: '\eb6a'; --vscode-icon-three-bars-font-family: 'codicon'; --vscode-icon-thumbsdown-content: '\eb6b'; --vscode-icon-thumbsdown-font-family: 'codicon'; --vscode-icon-thumbsup-content: '\eb6c'; --vscode-icon-thumbsup-font-family: 'codicon'; --vscode-icon-tools-content: '\eb6d'; --vscode-icon-tools-font-family: 'codicon'; --vscode-icon-triangle-down-content: '\eb6e'; --vscode-icon-triangle-down-font-family: 'codicon'; --vscode-icon-triangle-left-content: '\eb6f'; --vscode-icon-triangle-left-font-family: 'codicon'; --vscode-icon-triangle-right-content: '\eb70'; --vscode-icon-triangle-right-font-family: 'codicon'; --vscode-icon-triangle-up-content: '\eb71'; --vscode-icon-triangle-up-font-family: 'codicon'; --vscode-icon-twitter-content: '\eb72'; --vscode-icon-twitter-font-family: 'codicon'; --vscode-icon-unfold-content: '\eb73'; --vscode-icon-unfold-font-family: 'codicon'; --vscode-icon-unlock-content: '\eb74'; --vscode-icon-unlock-font-family: 'codicon'; --vscode-icon-unmute-content: '\eb75'; --vscode-icon-unmute-font-family: 'codicon'; --vscode-icon-unverified-content: '\eb76'; --vscode-icon-unverified-font-family: 'codicon'; --vscode-icon-verified-content: '\eb77'; --vscode-icon-verified-font-family: 'codicon'; --vscode-icon-versions-content: '\eb78'; --vscode-icon-versions-font-family: 'codicon'; --vscode-icon-vm-active-content: '\eb79'; --vscode-icon-vm-active-font-family: 'codicon'; --vscode-icon-vm-outline-content: '\eb7a'; --vscode-icon-vm-outline-font-family: 'codicon'; --vscode-icon-vm-running-content: '\eb7b'; --vscode-icon-vm-running-font-family: 'codicon'; --vscode-icon-watch-content: '\eb7c'; --vscode-icon-watch-font-family: 'codicon'; --vscode-icon-whitespace-content: '\eb7d'; --vscode-icon-whitespace-font-family: 'codicon'; --vscode-icon-whole-word-content: '\eb7e'; --vscode-icon-whole-word-font-family: 'codicon'; --vscode-icon-window-content: '\eb7f'; --vscode-icon-window-font-family: 'codicon'; --vscode-icon-word-wrap-content: '\eb80'; --vscode-icon-word-wrap-font-family: 'codicon'; --vscode-icon-zoom-in-content: '\eb81'; --vscode-icon-zoom-in-font-family: 'codicon'; --vscode-icon-zoom-out-content: '\eb82'; --vscode-icon-zoom-out-font-family: 'codicon'; --vscode-icon-list-filter-content: '\eb83'; --vscode-icon-list-filter-font-family: 'codicon'; --vscode-icon-list-flat-content: '\eb84'; --vscode-icon-list-flat-font-family: 'codicon'; --vscode-icon-list-selection-content: '\eb85'; --vscode-icon-list-selection-font-family: 'codicon'; --vscode-icon-selection-content: '\eb85'; --vscode-icon-selection-font-family: 'codicon'; --vscode-icon-list-tree-content: '\eb86'; --vscode-icon-list-tree-font-family: 'codicon'; --vscode-icon-debug-breakpoint-function-unverified-content: '\eb87'; --vscode-icon-debug-breakpoint-function-unverified-font-family: 'codicon'; --vscode-icon-debug-breakpoint-function-content: '\eb88'; --vscode-icon-debug-breakpoint-function-font-family: 'codicon'; --vscode-icon-debug-breakpoint-function-disabled-content: '\eb88'; --vscode-icon-debug-breakpoint-function-disabled-font-family: 'codicon'; --vscode-icon-debug-stackframe-active-content: '\eb89'; --vscode-icon-debug-stackframe-active-font-family: 'codicon'; --vscode-icon-circle-small-filled-content: '\eb8a'; --vscode-icon-circle-small-filled-font-family: 'codicon'; --vscode-icon-debug-stackframe-dot-content: '\eb8a'; --vscode-icon-debug-stackframe-dot-font-family: 'codicon'; --vscode-icon-terminal-decoration-mark-content: '\eb8a'; --vscode-icon-terminal-decoration-mark-font-family: 'codicon'; --vscode-icon-debug-stackframe-content: '\eb8b'; --vscode-icon-debug-stackframe-font-family: 'codicon'; --vscode-icon-debug-stackframe-focused-content: '\eb8b'; --vscode-icon-debug-stackframe-focused-font-family: 'codicon'; --vscode-icon-debug-breakpoint-unsupported-content: '\eb8c'; --vscode-icon-debug-breakpoint-unsupported-font-family: 'codicon'; --vscode-icon-symbol-string-content: '\eb8d'; --vscode-icon-symbol-string-font-family: 'codicon'; --vscode-icon-debug-reverse-continue-content: '\eb8e'; --vscode-icon-debug-reverse-continue-font-family: 'codicon'; --vscode-icon-debug-step-back-content: '\eb8f'; --vscode-icon-debug-step-back-font-family: 'codicon'; --vscode-icon-debug-restart-frame-content: '\eb90'; --vscode-icon-debug-restart-frame-font-family: 'codicon'; --vscode-icon-debug-alt-content: '\eb91'; --vscode-icon-debug-alt-font-family: 'codicon'; --vscode-icon-call-incoming-content: '\eb92'; --vscode-icon-call-incoming-font-family: 'codicon'; --vscode-icon-call-outgoing-content: '\eb93'; --vscode-icon-call-outgoing-font-family: 'codicon'; --vscode-icon-menu-content: '\eb94'; --vscode-icon-menu-font-family: 'codicon'; --vscode-icon-expand-all-content: '\eb95'; --vscode-icon-expand-all-font-family: 'codicon'; --vscode-icon-feedback-content: '\eb96'; --vscode-icon-feedback-font-family: 'codicon'; --vscode-icon-git-pull-request-reviewer-content: '\eb96'; --vscode-icon-git-pull-request-reviewer-font-family: 'codicon'; --vscode-icon-group-by-ref-type-content: '\eb97'; --vscode-icon-group-by-ref-type-font-family: 'codicon'; --vscode-icon-ungroup-by-ref-type-content: '\eb98'; --vscode-icon-ungroup-by-ref-type-font-family: 'codicon'; --vscode-icon-account-content: '\eb99'; --vscode-icon-account-font-family: 'codicon'; --vscode-icon-git-pull-request-assignee-content: '\eb99'; --vscode-icon-git-pull-request-assignee-font-family: 'codicon'; --vscode-icon-bell-dot-content: '\eb9a'; --vscode-icon-bell-dot-font-family: 'codicon'; --vscode-icon-debug-console-content: '\eb9b'; --vscode-icon-debug-console-font-family: 'codicon'; --vscode-icon-library-content: '\eb9c'; --vscode-icon-library-font-family: 'codicon'; --vscode-icon-output-content: '\eb9d'; --vscode-icon-output-font-family: 'codicon'; --vscode-icon-run-all-content: '\eb9e'; --vscode-icon-run-all-font-family: 'codicon'; --vscode-icon-sync-ignored-content: '\eb9f'; --vscode-icon-sync-ignored-font-family: 'codicon'; --vscode-icon-pinned-content: '\eba0'; --vscode-icon-pinned-font-family: 'codicon'; --vscode-icon-github-inverted-content: '\eba1'; --vscode-icon-github-inverted-font-family: 'codicon'; --vscode-icon-server-process-content: '\eba2'; --vscode-icon-server-process-font-family: 'codicon'; --vscode-icon-server-environment-content: '\eba3'; --vscode-icon-server-environment-font-family: 'codicon'; --vscode-icon-pass-content: '\eba4'; --vscode-icon-pass-font-family: 'codicon'; --vscode-icon-issue-closed-content: '\eba4'; --vscode-icon-issue-closed-font-family: 'codicon'; --vscode-icon-stop-circle-content: '\eba5'; --vscode-icon-stop-circle-font-family: 'codicon'; --vscode-icon-play-circle-content: '\eba6'; --vscode-icon-play-circle-font-family: 'codicon'; --vscode-icon-record-content: '\eba7'; --vscode-icon-record-font-family: 'codicon'; --vscode-icon-debug-alt-small-content: '\eba8'; --vscode-icon-debug-alt-small-font-family: 'codicon'; --vscode-icon-vm-connect-content: '\eba9'; --vscode-icon-vm-connect-font-family: 'codicon'; --vscode-icon-cloud-content: '\ebaa'; --vscode-icon-cloud-font-family: 'codicon'; --vscode-icon-merge-content: '\ebab'; --vscode-icon-merge-font-family: 'codicon'; --vscode-icon-export-content: '\ebac'; --vscode-icon-export-font-family: 'codicon'; --vscode-icon-graph-left-content: '\ebad'; --vscode-icon-graph-left-font-family: 'codicon'; --vscode-icon-magnet-content: '\ebae'; --vscode-icon-magnet-font-family: 'codicon'; --vscode-icon-notebook-content: '\ebaf'; --vscode-icon-notebook-font-family: 'codicon'; --vscode-icon-redo-content: '\ebb0'; --vscode-icon-redo-font-family: 'codicon'; --vscode-icon-check-all-content: '\ebb1'; --vscode-icon-check-all-font-family: 'codicon'; --vscode-icon-pinned-dirty-content: '\ebb2'; --vscode-icon-pinned-dirty-font-family: 'codicon'; --vscode-icon-pass-filled-content: '\ebb3'; --vscode-icon-pass-filled-font-family: 'codicon'; --vscode-icon-circle-large-filled-content: '\ebb4'; --vscode-icon-circle-large-filled-font-family: 'codicon'; --vscode-icon-circle-large-content: '\ebb5'; --vscode-icon-circle-large-font-family: 'codicon'; --vscode-icon-circle-large-outline-content: '\ebb5'; --vscode-icon-circle-large-outline-font-family: 'codicon'; --vscode-icon-combine-content: '\ebb6'; --vscode-icon-combine-font-family: 'codicon'; --vscode-icon-gather-content: '\ebb6'; --vscode-icon-gather-font-family: 'codicon'; --vscode-icon-table-content: '\ebb7'; --vscode-icon-table-font-family: 'codicon'; --vscode-icon-variable-group-content: '\ebb8'; --vscode-icon-variable-group-font-family: 'codicon'; --vscode-icon-type-hierarchy-content: '\ebb9'; --vscode-icon-type-hierarchy-font-family: 'codicon'; --vscode-icon-type-hierarchy-sub-content: '\ebba'; --vscode-icon-type-hierarchy-sub-font-family: 'codicon'; --vscode-icon-type-hierarchy-super-content: '\ebbb'; --vscode-icon-type-hierarchy-super-font-family: 'codicon'; --vscode-icon-git-pull-request-create-content: '\ebbc'; --vscode-icon-git-pull-request-create-font-family: 'codicon'; --vscode-icon-run-above-content: '\ebbd'; --vscode-icon-run-above-font-family: 'codicon'; --vscode-icon-run-below-content: '\ebbe'; --vscode-icon-run-below-font-family: 'codicon'; --vscode-icon-notebook-template-content: '\ebbf'; --vscode-icon-notebook-template-font-family: 'codicon'; --vscode-icon-debug-rerun-content: '\ebc0'; --vscode-icon-debug-rerun-font-family: 'codicon'; --vscode-icon-workspace-trusted-content: '\ebc1'; --vscode-icon-workspace-trusted-font-family: 'codicon'; --vscode-icon-workspace-untrusted-content: '\ebc2'; --vscode-icon-workspace-untrusted-font-family: 'codicon'; --vscode-icon-workspace-unknown-content: '\ebc3'; --vscode-icon-workspace-unknown-font-family: 'codicon'; --vscode-icon-terminal-cmd-content: '\ebc4'; --vscode-icon-terminal-cmd-font-family: 'codicon'; --vscode-icon-terminal-debian-content: '\ebc5'; --vscode-icon-terminal-debian-font-family: 'codicon'; --vscode-icon-terminal-linux-content: '\ebc6'; --vscode-icon-terminal-linux-font-family: 'codicon'; --vscode-icon-terminal-powershell-content: '\ebc7'; --vscode-icon-terminal-powershell-font-family: 'codicon'; --vscode-icon-terminal-tmux-content: '\ebc8'; --vscode-icon-terminal-tmux-font-family: 'codicon'; --vscode-icon-terminal-ubuntu-content: '\ebc9'; --vscode-icon-terminal-ubuntu-font-family: 'codicon'; --vscode-icon-terminal-bash-content: '\ebca'; --vscode-icon-terminal-bash-font-family: 'codicon'; --vscode-icon-arrow-swap-content: '\ebcb'; --vscode-icon-arrow-swap-font-family: 'codicon'; --vscode-icon-copy-content: '\ebcc'; --vscode-icon-copy-font-family: 'codicon'; --vscode-icon-person-add-content: '\ebcd'; --vscode-icon-person-add-font-family: 'codicon'; --vscode-icon-filter-filled-content: '\ebce'; --vscode-icon-filter-filled-font-family: 'codicon'; --vscode-icon-wand-content: '\ebcf'; --vscode-icon-wand-font-family: 'codicon'; --vscode-icon-debug-line-by-line-content: '\ebd0'; --vscode-icon-debug-line-by-line-font-family: 'codicon'; --vscode-icon-inspect-content: '\ebd1'; --vscode-icon-inspect-font-family: 'codicon'; --vscode-icon-layers-content: '\ebd2'; --vscode-icon-layers-font-family: 'codicon'; --vscode-icon-layers-dot-content: '\ebd3'; --vscode-icon-layers-dot-font-family: 'codicon'; --vscode-icon-layers-active-content: '\ebd4'; --vscode-icon-layers-active-font-family: 'codicon'; --vscode-icon-compass-content: '\ebd5'; --vscode-icon-compass-font-family: 'codicon'; --vscode-icon-compass-dot-content: '\ebd6'; --vscode-icon-compass-dot-font-family: 'codicon'; --vscode-icon-compass-active-content: '\ebd7'; --vscode-icon-compass-active-font-family: 'codicon'; --vscode-icon-azure-content: '\ebd8'; --vscode-icon-azure-font-family: 'codicon'; --vscode-icon-issue-draft-content: '\ebd9'; --vscode-icon-issue-draft-font-family: 'codicon'; --vscode-icon-git-pull-request-closed-content: '\ebda'; --vscode-icon-git-pull-request-closed-font-family: 'codicon'; --vscode-icon-git-pull-request-draft-content: '\ebdb'; --vscode-icon-git-pull-request-draft-font-family: 'codicon'; --vscode-icon-debug-all-content: '\ebdc'; --vscode-icon-debug-all-font-family: 'codicon'; --vscode-icon-debug-coverage-content: '\ebdd'; --vscode-icon-debug-coverage-font-family: 'codicon'; --vscode-icon-run-errors-content: '\ebde'; --vscode-icon-run-errors-font-family: 'codicon'; --vscode-icon-folder-library-content: '\ebdf'; --vscode-icon-folder-library-font-family: 'codicon'; --vscode-icon-debug-continue-small-content: '\ebe0'; --vscode-icon-debug-continue-small-font-family: 'codicon'; --vscode-icon-beaker-stop-content: '\ebe1'; --vscode-icon-beaker-stop-font-family: 'codicon'; --vscode-icon-graph-line-content: '\ebe2'; --vscode-icon-graph-line-font-family: 'codicon'; --vscode-icon-graph-scatter-content: '\ebe3'; --vscode-icon-graph-scatter-font-family: 'codicon'; --vscode-icon-pie-chart-content: '\ebe4'; --vscode-icon-pie-chart-font-family: 'codicon'; --vscode-icon-bracket-content: '\eb0f'; --vscode-icon-bracket-font-family: 'codicon'; --vscode-icon-bracket-dot-content: '\ebe5'; --vscode-icon-bracket-dot-font-family: 'codicon'; --vscode-icon-bracket-error-content: '\ebe6'; --vscode-icon-bracket-error-font-family: 'codicon'; --vscode-icon-lock-small-content: '\ebe7'; --vscode-icon-lock-small-font-family: 'codicon'; --vscode-icon-azure-devops-content: '\ebe8'; --vscode-icon-azure-devops-font-family: 'codicon'; --vscode-icon-verified-filled-content: '\ebe9'; --vscode-icon-verified-filled-font-family: 'codicon'; --vscode-icon-newline-content: '\ebea'; --vscode-icon-newline-font-family: 'codicon'; --vscode-icon-layout-content: '\ebeb'; --vscode-icon-layout-font-family: 'codicon'; --vscode-icon-layout-activitybar-left-content: '\ebec'; --vscode-icon-layout-activitybar-left-font-family: 'codicon'; --vscode-icon-layout-activitybar-right-content: '\ebed'; --vscode-icon-layout-activitybar-right-font-family: 'codicon'; --vscode-icon-layout-panel-left-content: '\ebee'; --vscode-icon-layout-panel-left-font-family: 'codicon'; --vscode-icon-layout-panel-center-content: '\ebef'; --vscode-icon-layout-panel-center-font-family: 'codicon'; --vscode-icon-layout-panel-justify-content: '\ebf0'; --vscode-icon-layout-panel-justify-font-family: 'codicon'; --vscode-icon-layout-panel-right-content: '\ebf1'; --vscode-icon-layout-panel-right-font-family: 'codicon'; --vscode-icon-layout-panel-content: '\ebf2'; --vscode-icon-layout-panel-font-family: 'codicon'; --vscode-icon-layout-sidebar-left-content: '\ebf3'; --vscode-icon-layout-sidebar-left-font-family: 'codicon'; --vscode-icon-layout-sidebar-right-content: '\ebf4'; --vscode-icon-layout-sidebar-right-font-family: 'codicon'; --vscode-icon-layout-statusbar-content: '\ebf5'; --vscode-icon-layout-statusbar-font-family: 'codicon'; --vscode-icon-layout-menubar-content: '\ebf6'; --vscode-icon-layout-menubar-font-family: 'codicon'; --vscode-icon-layout-centered-content: '\ebf7'; --vscode-icon-layout-centered-font-family: 'codicon'; --vscode-icon-target-content: '\ebf8'; --vscode-icon-target-font-family: 'codicon'; --vscode-icon-indent-content: '\ebf9'; --vscode-icon-indent-font-family: 'codicon'; --vscode-icon-record-small-content: '\ebfa'; --vscode-icon-record-small-font-family: 'codicon'; --vscode-icon-error-small-content: '\ebfb'; --vscode-icon-error-small-font-family: 'codicon'; --vscode-icon-terminal-decoration-error-content: '\ebfb'; --vscode-icon-terminal-decoration-error-font-family: 'codicon'; --vscode-icon-arrow-circle-down-content: '\ebfc'; --vscode-icon-arrow-circle-down-font-family: 'codicon'; --vscode-icon-arrow-circle-left-content: '\ebfd'; --vscode-icon-arrow-circle-left-font-family: 'codicon'; --vscode-icon-arrow-circle-right-content: '\ebfe'; --vscode-icon-arrow-circle-right-font-family: 'codicon'; --vscode-icon-arrow-circle-up-content: '\ebff'; --vscode-icon-arrow-circle-up-font-family: 'codicon'; --vscode-icon-layout-sidebar-right-off-content: '\ec00'; --vscode-icon-layout-sidebar-right-off-font-family: 'codicon'; --vscode-icon-layout-panel-off-content: '\ec01'; --vscode-icon-layout-panel-off-font-family: 'codicon'; --vscode-icon-layout-sidebar-left-off-content: '\ec02'; --vscode-icon-layout-sidebar-left-off-font-family: 'codicon'; --vscode-icon-blank-content: '\ec03'; --vscode-icon-blank-font-family: 'codicon'; --vscode-icon-heart-filled-content: '\ec04'; --vscode-icon-heart-filled-font-family: 'codicon'; --vscode-icon-map-content: '\ec05'; --vscode-icon-map-font-family: 'codicon'; --vscode-icon-map-horizontal-content: '\ec05'; --vscode-icon-map-horizontal-font-family: 'codicon'; --vscode-icon-fold-horizontal-content: '\ec05'; --vscode-icon-fold-horizontal-font-family: 'codicon'; --vscode-icon-map-filled-content: '\ec06'; --vscode-icon-map-filled-font-family: 'codicon'; --vscode-icon-map-horizontal-filled-content: '\ec06'; --vscode-icon-map-horizontal-filled-font-family: 'codicon'; --vscode-icon-fold-horizontal-filled-content: '\ec06'; --vscode-icon-fold-horizontal-filled-font-family: 'codicon'; --vscode-icon-circle-small-content: '\ec07'; --vscode-icon-circle-small-font-family: 'codicon'; --vscode-icon-bell-slash-content: '\ec08'; --vscode-icon-bell-slash-font-family: 'codicon'; --vscode-icon-bell-slash-dot-content: '\ec09'; --vscode-icon-bell-slash-dot-font-family: 'codicon'; --vscode-icon-comment-unresolved-content: '\ec0a'; --vscode-icon-comment-unresolved-font-family: 'codicon'; --vscode-icon-git-pull-request-go-to-changes-content: '\ec0b'; --vscode-icon-git-pull-request-go-to-changes-font-family: 'codicon'; --vscode-icon-git-pull-request-new-changes-content: '\ec0c'; --vscode-icon-git-pull-request-new-changes-font-family: 'codicon'; --vscode-icon-search-fuzzy-content: '\ec0d'; --vscode-icon-search-fuzzy-font-family: 'codicon'; --vscode-icon-comment-draft-content: '\ec0e'; --vscode-icon-comment-draft-font-family: 'codicon'; --vscode-icon-send-content: '\ec0f'; --vscode-icon-send-font-family: 'codicon'; --vscode-icon-sparkle-content: '\ec10'; --vscode-icon-sparkle-font-family: 'codicon'; --vscode-icon-insert-content: '\ec11'; --vscode-icon-insert-font-family: 'codicon'; --vscode-icon-mic-content: '\ec12'; --vscode-icon-mic-font-family: 'codicon'; --vscode-icon-thumbsdown-filled-content: '\ec13'; --vscode-icon-thumbsdown-filled-font-family: 'codicon'; --vscode-icon-thumbsup-filled-content: '\ec14'; --vscode-icon-thumbsup-filled-font-family: 'codicon'; --vscode-icon-coffee-content: '\ec15'; --vscode-icon-coffee-font-family: 'codicon'; --vscode-icon-snake-content: '\ec16'; --vscode-icon-snake-font-family: 'codicon'; --vscode-icon-game-content: '\ec17'; --vscode-icon-game-font-family: 'codicon'; --vscode-icon-vr-content: '\ec18'; --vscode-icon-vr-font-family: 'codicon'; --vscode-icon-chip-content: '\ec19'; --vscode-icon-chip-font-family: 'codicon'; --vscode-icon-piano-content: '\ec1a'; --vscode-icon-piano-font-family: 'codicon'; --vscode-icon-music-content: '\ec1b'; --vscode-icon-music-font-family: 'codicon'; --vscode-icon-mic-filled-content: '\ec1c'; --vscode-icon-mic-filled-font-family: 'codicon'; --vscode-icon-repo-fetch-content: '\ec1d'; --vscode-icon-repo-fetch-font-family: 'codicon'; --vscode-icon-copilot-content: '\ec1e'; --vscode-icon-copilot-font-family: 'codicon'; --vscode-icon-lightbulb-sparkle-content: '\ec1f'; --vscode-icon-lightbulb-sparkle-font-family: 'codicon'; --vscode-icon-robot-content: '\ec20'; --vscode-icon-robot-font-family: 'codicon'; --vscode-icon-sparkle-filled-content: '\ec21'; --vscode-icon-sparkle-filled-font-family: 'codicon'; --vscode-icon-diff-single-content: '\ec22'; --vscode-icon-diff-single-font-family: 'codicon'; --vscode-icon-diff-multiple-content: '\ec23'; --vscode-icon-diff-multiple-font-family: 'codicon'; --vscode-icon-surround-with-content: '\ec24'; --vscode-icon-surround-with-font-family: 'codicon'; --vscode-icon-share-content: '\ec25'; --vscode-icon-share-font-family: 'codicon'; --vscode-icon-git-stash-content: '\ec26'; --vscode-icon-git-stash-font-family: 'codicon'; --vscode-icon-git-stash-apply-content: '\ec27'; --vscode-icon-git-stash-apply-font-family: 'codicon'; --vscode-icon-git-stash-pop-content: '\ec28'; --vscode-icon-git-stash-pop-font-family: 'codicon'; --vscode-icon-vscode-content: '\ec29'; --vscode-icon-vscode-font-family: 'codicon'; --vscode-icon-vscode-insiders-content: '\ec2a'; --vscode-icon-vscode-insiders-font-family: 'codicon'; --vscode-icon-code-oss-content: '\ec2b'; --vscode-icon-code-oss-font-family: 'codicon'; --vscode-icon-run-coverage-content: '\ec2c'; --vscode-icon-run-coverage-font-family: 'codicon'; --vscode-icon-run-all-coverage-content: '\ec2d'; --vscode-icon-run-all-coverage-font-family: 'codicon'; --vscode-icon-coverage-content: '\ec2e'; --vscode-icon-coverage-font-family: 'codicon'; --vscode-icon-github-project-content: '\ec2f'; --vscode-icon-github-project-font-family: 'codicon'; --vscode-icon-map-vertical-content: '\ec30'; --vscode-icon-map-vertical-font-family: 'codicon'; --vscode-icon-fold-vertical-content: '\ec30'; --vscode-icon-fold-vertical-font-family: 'codicon'; --vscode-icon-map-vertical-filled-content: '\ec31'; --vscode-icon-map-vertical-filled-font-family: 'codicon'; --vscode-icon-fold-vertical-filled-content: '\ec31'; --vscode-icon-fold-vertical-filled-font-family: 'codicon'; --vscode-icon-go-to-search-content: '\ec32'; --vscode-icon-go-to-search-font-family: 'codicon'; --vscode-icon-percentage-content: '\ec33'; --vscode-icon-percentage-font-family: 'codicon'; --vscode-icon-sort-percentage-content: '\ec33'; --vscode-icon-sort-percentage-font-family: 'codicon'; --vscode-icon-attach-content: '\ec34'; --vscode-icon-attach-font-family: 'codicon'; --vscode-icon-dialog-error-content: '\ea87'; --vscode-icon-dialog-error-font-family: 'codicon'; --vscode-icon-dialog-warning-content: '\ea6c'; --vscode-icon-dialog-warning-font-family: 'codicon'; --vscode-icon-dialog-info-content: '\ea74'; --vscode-icon-dialog-info-font-family: 'codicon'; --vscode-icon-dialog-close-content: '\ea76'; --vscode-icon-dialog-close-font-family: 'codicon'; --vscode-icon-tree-item-expanded-content: '\eab4'; --vscode-icon-tree-item-expanded-font-family: 'codicon'; --vscode-icon-tree-filter-on-type-on-content: '\eb83'; --vscode-icon-tree-filter-on-type-on-font-family: 'codicon'; --vscode-icon-tree-filter-on-type-off-content: '\eb85'; --vscode-icon-tree-filter-on-type-off-font-family: 'codicon'; --vscode-icon-tree-filter-clear-content: '\ea76'; --vscode-icon-tree-filter-clear-font-family: 'codicon'; --vscode-icon-tree-item-loading-content: '\eb19'; --vscode-icon-tree-item-loading-font-family: 'codicon'; --vscode-icon-menu-selection-content: '\eab2'; --vscode-icon-menu-selection-font-family: 'codicon'; --vscode-icon-menu-submenu-content: '\eab6'; --vscode-icon-menu-submenu-font-family: 'codicon'; --vscode-icon-menubar-more-content: '\ea7c'; --vscode-icon-menubar-more-font-family: 'codicon'; --vscode-icon-scrollbar-button-left-content: '\eb6f'; --vscode-icon-scrollbar-button-left-font-family: 'codicon'; --vscode-icon-scrollbar-button-right-content: '\eb70'; --vscode-icon-scrollbar-button-right-font-family: 'codicon'; --vscode-icon-scrollbar-button-up-content: '\eb71'; --vscode-icon-scrollbar-button-up-font-family: 'codicon'; --vscode-icon-scrollbar-button-down-content: '\eb6e'; --vscode-icon-scrollbar-button-down-font-family: 'codicon'; --vscode-icon-toolbar-more-content: '\ea7c'; --vscode-icon-toolbar-more-font-family: 'codicon'; --vscode-icon-quick-input-back-content: '\ea9b'; --vscode-icon-quick-input-back-font-family: 'codicon'; --vscode-icon-drop-down-button-content: '\eab4'; --vscode-icon-drop-down-button-font-family: 'codicon'; --vscode-icon-symbol-customcolor-content: '\eb5c'; --vscode-icon-symbol-customcolor-font-family: 'codicon'; --vscode-icon-workspace-unspecified-content: '\ebc3'; --vscode-icon-workspace-unspecified-font-family: 'codicon'; --vscode-icon-git-fetch-content: '\ec1d'; --vscode-icon-git-fetch-font-family: 'codicon'; --vscode-icon-lightbulb-sparkle-autofix-content: '\ec1f'; --vscode-icon-lightbulb-sparkle-autofix-font-family: 'codicon'; --vscode-icon-debug-breakpoint-pending-content: '\ebd9'; --vscode-icon-debug-breakpoint-pending-font-family: 'codicon'; --vscode-icon-widget-close-content: '\ea76'; --vscode-icon-widget-close-font-family: 'codicon'; --vscode-icon-goto-previous-location-content: '\eaa1'; --vscode-icon-goto-previous-location-font-family: 'codicon'; --vscode-icon-goto-next-location-content: '\ea9a'; --vscode-icon-goto-next-location-font-family: 'codicon'; --vscode-icon-diff-review-insert-content: '\ea60'; --vscode-icon-diff-review-insert-font-family: 'codicon'; --vscode-icon-diff-review-remove-content: '\eb3b'; --vscode-icon-diff-review-remove-font-family: 'codicon'; --vscode-icon-diff-review-close-content: '\ea76'; --vscode-icon-diff-review-close-font-family: 'codicon'; --vscode-icon-diff-insert-content: '\ea60'; --vscode-icon-diff-insert-font-family: 'codicon'; --vscode-icon-diff-remove-content: '\eb3b'; --vscode-icon-diff-remove-font-family: 'codicon'; --vscode-icon-gutter-lightbulb-content: '\ea61'; --vscode-icon-gutter-lightbulb-font-family: 'codicon'; --vscode-icon-gutter-lightbulb-auto-fix-content: '\eb13'; --vscode-icon-gutter-lightbulb-auto-fix-font-family: 'codicon'; --vscode-icon-gutter-lightbulb-sparkle-content: '\ec1f'; --vscode-icon-gutter-lightbulb-sparkle-font-family: 'codicon'; --vscode-icon-gutter-lightbulb-aifix-auto-fix-content: '\ec1f'; --vscode-icon-gutter-lightbulb-aifix-auto-fix-font-family: 'codicon'; --vscode-icon-gutter-lightbulb-sparkle-filled-content: '\ec21'; --vscode-icon-gutter-lightbulb-sparkle-filled-font-family: 'codicon'; --vscode-icon-inline-suggestion-hints-next-content: '\eab6'; --vscode-icon-inline-suggestion-hints-next-font-family: 'codicon'; --vscode-icon-inline-suggestion-hints-previous-content: '\eab5'; --vscode-icon-inline-suggestion-hints-previous-font-family: 'codicon'; --vscode-icon-hover-increase-verbosity-content: '\ea60'; --vscode-icon-hover-increase-verbosity-font-family: 'codicon'; --vscode-icon-hover-decrease-verbosity-content: '\eb3b'; --vscode-icon-hover-decrease-verbosity-font-family: 'codicon'; --vscode-icon-find-collapsed-content: '\eab6'; --vscode-icon-find-collapsed-font-family: 'codicon'; --vscode-icon-find-expanded-content: '\eab4'; --vscode-icon-find-expanded-font-family: 'codicon'; --vscode-icon-find-selection-content: '\eb85'; --vscode-icon-find-selection-font-family: 'codicon'; --vscode-icon-find-replace-content: '\eb3d'; --vscode-icon-find-replace-font-family: 'codicon'; --vscode-icon-find-replace-all-content: '\eb3c'; --vscode-icon-find-replace-all-font-family: 'codicon'; --vscode-icon-find-previous-match-content: '\eaa1'; --vscode-icon-find-previous-match-font-family: 'codicon'; --vscode-icon-find-next-match-content: '\ea9a'; --vscode-icon-find-next-match-font-family: 'codicon'; --vscode-icon-folding-expanded-content: '\eab4'; --vscode-icon-folding-expanded-font-family: 'codicon'; --vscode-icon-folding-collapsed-content: '\eab6'; --vscode-icon-folding-collapsed-font-family: 'codicon'; --vscode-icon-folding-manual-collapsed-content: '\eab6'; --vscode-icon-folding-manual-collapsed-font-family: 'codicon'; --vscode-icon-folding-manual-expanded-content: '\eab4'; --vscode-icon-folding-manual-expanded-font-family: 'codicon'; --vscode-icon-suggest-more-info-content: '\eab6'; --vscode-icon-suggest-more-info-font-family: 'codicon'; --vscode-icon-marker-navigation-next-content: '\ea9a'; --vscode-icon-marker-navigation-next-font-family: 'codicon'; --vscode-icon-marker-navigation-previous-content: '\eaa1'; --vscode-icon-marker-navigation-previous-font-family: 'codicon'; --vscode-icon-parameter-hints-next-content: '\eab4'; --vscode-icon-parameter-hints-next-font-family: 'codicon'; --vscode-icon-parameter-hints-previous-content: '\eab7'; --vscode-icon-parameter-hints-previous-font-family: 'codicon'; --vscode-icon-extensions-warning-message-content: '\ea6c'; --vscode-icon-extensions-warning-message-font-family: 'codicon'; }
.monaco-workbench .workbench-hover .hover-row:not(:first-child):not(:empty) { border-top: 1px solid rgba(200, 200, 200, 0.5); }
.monaco-workbench .workbench-hover hr { border-top: 1px solid rgba(200, 200, 200, 0.5); }
.monaco-editor .inputarea.ime-input { background-color: #fffffe; }
.monaco-editor .unexpected-closing-bracket { color: rgba(255, 18, 18, 0.8); }
.monaco-editor .bracket-highlighting-0 { color: #0431fa; }
.monaco-editor .bracket-highlighting-1 { color: #319331; }
.monaco-editor .bracket-highlighting-2 { color: #7b3814; }
.monaco-editor .bracket-highlighting-3 { color: #0431fa; }
.monaco-editor .bracket-highlighting-4 { color: #319331; }
.monaco-editor .bracket-highlighting-5 { color: #7b3814; }
.monaco-editor .bracket-highlighting-6 { color: #0431fa; }
.monaco-editor .bracket-highlighting-7 { color: #319331; }
.monaco-editor .bracket-highlighting-8 { color: #7b3814; }
.monaco-editor .bracket-highlighting-9 { color: #0431fa; }
.monaco-editor .bracket-highlighting-10 { color: #319331; }
.monaco-editor .bracket-highlighting-11 { color: #7b3814; }
.monaco-editor .bracket-highlighting-12 { color: #0431fa; }
.monaco-editor .bracket-highlighting-13 { color: #319331; }
.monaco-editor .bracket-highlighting-14 { color: #7b3814; }
.monaco-editor .bracket-highlighting-15 { color: #0431fa; }
.monaco-editor .bracket-highlighting-16 { color: #319331; }
.monaco-editor .bracket-highlighting-17 { color: #7b3814; }
.monaco-editor .bracket-highlighting-18 { color: #0431fa; }
.monaco-editor .bracket-highlighting-19 { color: #319331; }
.monaco-editor .bracket-highlighting-20 { color: #7b3814; }
.monaco-editor .bracket-highlighting-21 { color: #0431fa; }
.monaco-editor .bracket-highlighting-22 { color: #319331; }
.monaco-editor .bracket-highlighting-23 { color: #7b3814; }
.monaco-editor .bracket-highlighting-24 { color: #0431fa; }
.monaco-editor .bracket-highlighting-25 { color: #319331; }
.monaco-editor .bracket-highlighting-26 { color: #7b3814; }
.monaco-editor .bracket-highlighting-27 { color: #0431fa; }
.monaco-editor .bracket-highlighting-28 { color: #319331; }
.monaco-editor .bracket-highlighting-29 { color: #7b3814; }
.monaco-editor .line-numbers.dimmed-line-number { color: rgba(35, 120, 147, 0.4); }
.monaco-editor .view-overlays .current-line-exact { border: 2px solid #eeeeee; }
.monaco-editor .margin-view-overlays .current-line-exact-margin { border: 2px solid #eeeeee; }
.monaco-editor .bracket-indent-guide.lvl-0 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-1 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-2 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-3 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-4 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-5 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-6 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-7 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-8 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-9 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-10 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-11 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-12 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-13 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-14 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-15 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-16 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-17 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-18 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-19 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-20 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-21 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-22 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-23 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-24 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-25 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-26 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .bracket-indent-guide.lvl-27 { --guide-color: rgba(4, 49, 250, 0.3); --guide-color-active: #0431fa; }
.monaco-editor .bracket-indent-guide.lvl-28 { --guide-color: rgba(49, 147, 49, 0.3); --guide-color-active: #319331; }
.monaco-editor .bracket-indent-guide.lvl-29 { --guide-color: rgba(123, 56, 20, 0.3); --guide-color-active: #7b3814; }
.monaco-editor .vertical { box-shadow: 1px 0 0 0 var(--guide-color) inset; }
.monaco-editor .horizontal-top { border-top: 1px solid var(--guide-color); }
.monaco-editor .horizontal-bottom { border-bottom: 1px solid var(--guide-color); }
.monaco-editor .vertical.indent-active { box-shadow: 1px 0 0 0 var(--guide-color-active) inset; }
.monaco-editor .horizontal-top.indent-active { border-top: 1px solid var(--guide-color-active); }
.monaco-editor .horizontal-bottom.indent-active { border-bottom: 1px solid var(--guide-color-active); }
.monaco-editor .lines-content .core-guide-indent.lvl-0 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-1 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-2 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-3 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-4 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-5 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-6 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-7 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-8 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-9 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-10 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-11 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-12 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-13 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-14 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-15 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-16 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-17 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-18 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-19 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-20 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-21 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-22 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-23 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-24 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-25 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-26 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-27 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-28 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent.lvl-29 { --indent-color: #d3d3d3; --indent-color-active: #939393; }
.monaco-editor .lines-content .core-guide-indent { box-shadow: 1px 0 0 0 var(--indent-color) inset; }
.monaco-editor .lines-content .core-guide-indent.indent-active { box-shadow: 1px 0 0 0 var(--indent-color-active) inset; }
.monaco-editor .cursors-layer .cursor { background-color: #000000; border-color: #000000; color: #ffffff; }
.monaco-editor .cursors-layer .cursor-primary { background-color: #000000; border-color: #000000; color: #ffffff; }
.monaco-editor .cursors-layer .cursor-secondary { background-color: #000000; border-color: #000000; color: #ffffff; }
.monaco-editor .squiggly-error { background: url("data:image/svg+xml,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%206%203'%20enable-background%3D'new%200%200%206%203'%20height%3D'3'%20width%3D'6'%3E%3Cg%20fill%3D'%23e51400'%3E%3Cpolygon%20points%3D'5.5%2C0%202.5%2C3%201.1%2C3%204.1%2C0'%2F%3E%3Cpolygon%20points%3D'4%2C0%206%2C2%206%2C0.6%205.4%2C0'%2F%3E%3Cpolygon%20points%3D'0%2C2%201%2C3%202.4%2C3%200%2C0.6'%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E") repeat-x bottom left; }
.monaco-editor .squiggly-warning { background: url("data:image/svg+xml,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%206%203'%20enable-background%3D'new%200%200%206%203'%20height%3D'3'%20width%3D'6'%3E%3Cg%20fill%3D'%23bf8803'%3E%3Cpolygon%20points%3D'5.5%2C0%202.5%2C3%201.1%2C3%204.1%2C0'%2F%3E%3Cpolygon%20points%3D'4%2C0%206%2C2%206%2C0.6%205.4%2C0'%2F%3E%3Cpolygon%20points%3D'0%2C2%201%2C3%202.4%2C3%200%2C0.6'%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E") repeat-x bottom left; }
.monaco-editor .squiggly-info { background: url("data:image/svg+xml,%3Csvg%20xmlns%3D'http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg'%20viewBox%3D'0%200%206%203'%20enable-background%3D'new%200%200%206%203'%20height%3D'3'%20width%3D'6'%3E%3Cg%20fill%3D'%231a85ff'%3E%3Cpolygon%20points%3D'5.5%2C0%202.5%2C3%201.1%2C3%204.1%2C0'%2F%3E%3Cpolygon%20points%3D'4%2C0%206%2C2%206%2C0.6%205.4%2C0'%2F%3E%3Cpolygon%20points%3D'0%2C2%201%2C3%202.4%2C3%200%2C0.6'%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E") repeat-x bottom left; }
.monaco-editor .squiggly-hint { background: url("data:image/svg+xml,%3Csvg%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%20height%3D%223%22%20width%3D%2212%22%3E%3Cg%20fill%3D%22%236c6c6c%22%3E%3Ccircle%20cx%3D%221%22%20cy%3D%221%22%20r%3D%221%22%2F%3E%3Ccircle%20cx%3D%225%22%20cy%3D%221%22%20r%3D%221%22%2F%3E%3Ccircle%20cx%3D%229%22%20cy%3D%221%22%20r%3D%221%22%2F%3E%3C%2Fg%3E%3C%2Fsvg%3E") no-repeat bottom left; }
.monaco-editor.showUnused .squiggly-inline-unnecessary { opacity: 0.467; }
.monaco-editor .quickfix-edit-highlight { background-color: rgba(234, 92, 0, 0.33); }
.monaco-editor .monaco-hover .hover-row:not(:first-child):not(:empty) { border-top: 1px solid rgba(200, 200, 200, 0.5); }
.monaco-editor .monaco-hover hr { border-top: 1px solid rgba(200, 200, 200, 0.5); }
.monaco-editor .monaco-hover hr { border-bottom: 0px solid rgba(200, 200, 200, 0.5); }
.monaco-editor .selectionHighlight { background-color: rgba(173, 214, 255, 0.15); }
.monaco-editor, .monaco-diff-editor, .monaco-component { --vscode-foreground: #616161;
--vscode-disabledForeground: rgba(97, 97, 97, 0.5);
--vscode-errorForeground: #a1260d;
--vscode-descriptionForeground: #717171;
--vscode-icon-foreground: #424242;
--vscode-focusBorder: #0090f1;
--vscode-textLink-foreground: #006ab1;
--vscode-textLink-activeForeground: #006ab1;
--vscode-textSeparator-foreground: rgba(0, 0, 0, 0.18);
--vscode-textPreformat-foreground: #a31515;
--vscode-textPreformat-background: rgba(0, 0, 0, 0.1);
--vscode-textBlockQuote-background: #f2f2f2;
--vscode-textBlockQuote-border: rgba(0, 122, 204, 0.5);
--vscode-textCodeBlock-background: rgba(220, 220, 220, 0.4);
--vscode-sash-hoverBorder: #0090f1;
--vscode-badge-background: #c4c4c4;
--vscode-badge-foreground: #333333;
--vscode-scrollbar-shadow: #dddddd;
--vscode-scrollbarSlider-background: rgba(100, 100, 100, 0.4);
--vscode-scrollbarSlider-hoverBackground: rgba(100, 100, 100, 0.7);
--vscode-scrollbarSlider-activeBackground: rgba(0, 0, 0, 0.6);
--vscode-progressBar-background: #0e70c0;
--vscode-editor-background: #fffffe;
--vscode-editor-foreground: #000000;
--vscode-editorStickyScroll-background: #fffffe;
--vscode-editorStickyScrollHover-background: #f0f0f0;
--vscode-editorStickyScroll-shadow: #dddddd;
--vscode-editorWidget-background: #f3f3f3;
--vscode-editorWidget-foreground: #616161;
--vscode-editorWidget-border: #c8c8c8;
--vscode-editorError-foreground: #e51400;
--vscode-editorWarning-foreground: #bf8803;
--vscode-editorInfo-foreground: #1a85ff;
--vscode-editorHint-foreground: #6c6c6c;
--vscode-editorLink-activeForeground: #0000ff;
--vscode-editor-selectionBackground: #add6ff;
--vscode-editor-inactiveSelectionBackground: #e5ebf1;
--vscode-editor-selectionHighlightBackground: rgba(173, 214, 255, 0.3);
--vscode-editor-findMatchBackground: #a8ac94;
--vscode-editor-findMatchHighlightBackground: rgba(234, 92, 0, 0.33);
--vscode-editor-findRangeHighlightBackground: rgba(180, 180, 180, 0.3);
--vscode-editor-hoverHighlightBackground: rgba(173, 214, 255, 0.15);
--vscode-editorHoverWidget-background: #f3f3f3;
--vscode-editorHoverWidget-foreground: #616161;
--vscode-editorHoverWidget-border: #c8c8c8;
--vscode-editorHoverWidget-statusBarBackground: #e7e7e7;
--vscode-editorInlayHint-foreground: #969696;
--vscode-editorInlayHint-background: rgba(196, 196, 196, 0.1);
--vscode-editorInlayHint-typeForeground: #969696;
--vscode-editorInlayHint-typeBackground: rgba(196, 196, 196, 0.1);
--vscode-editorInlayHint-parameterForeground: #969696;
--vscode-editorInlayHint-parameterBackground: rgba(196, 196, 196, 0.1);
--vscode-editorLightBulb-foreground: #ddb100;
--vscode-editorLightBulbAutoFix-foreground: #007acc;
--vscode-editorLightBulbAi-foreground: #ddb100;
--vscode-editor-snippetTabstopHighlightBackground: rgba(10, 50, 100, 0.2);
--vscode-editor-snippetFinalTabstopHighlightBorder: rgba(10, 50, 100, 0.5);
--vscode-diffEditor-insertedTextBackground: rgba(156, 204, 44, 0.25);
--vscode-diffEditor-removedTextBackground: rgba(255, 0, 0, 0.2);
--vscode-diffEditor-insertedLineBackground: rgba(155, 185, 85, 0.2);
--vscode-diffEditor-removedLineBackground: rgba(255, 0, 0, 0.2);
--vscode-diffEditor-diagonalFill: rgba(34, 34, 34, 0.2);
--vscode-diffEditor-unchangedRegionForeground: #616161;
--vscode-diffEditor-unchangedCodeBackground: rgba(184, 184, 184, 0.16);
--vscode-widget-shadow: rgba(0, 0, 0, 0.16);
--vscode-toolbar-hoverBackground: rgba(184, 184, 184, 0.31);
--vscode-toolbar-activeBackground: rgba(166, 166, 166, 0.31);
--vscode-breadcrumb-foreground: rgba(97, 97, 97, 0.8);
--vscode-breadcrumb-background: #fffffe;
--vscode-breadcrumb-focusForeground: #4e4e4e;
--vscode-breadcrumb-activeSelectionForeground: #4e4e4e;
--vscode-breadcrumbPicker-background: #f3f3f3;
--vscode-merge-currentHeaderBackground: rgba(64, 200, 174, 0.5);
--vscode-merge-currentContentBackground: rgba(64, 200, 174, 0.2);
--vscode-merge-incomingHeaderBackground: rgba(64, 166, 255, 0.5);
--vscode-merge-incomingContentBackground: rgba(64, 166, 255, 0.2);
--vscode-merge-commonHeaderBackground: rgba(96, 96, 96, 0.4);
--vscode-merge-commonContentBackground: rgba(96, 96, 96, 0.16);
--vscode-editorOverviewRuler-currentContentForeground: rgba(64, 200, 174, 0.5);
--vscode-editorOverviewRuler-incomingContentForeground: rgba(64, 166, 255, 0.5);
--vscode-editorOverviewRuler-commonContentForeground: rgba(96, 96, 96, 0.4);
--vscode-editorOverviewRuler-findMatchForeground: rgba(209, 134, 22, 0.49);
--vscode-editorOverviewRuler-selectionHighlightForeground: rgba(160, 160, 160, 0.8);
--vscode-problemsErrorIcon-foreground: #e51400;
--vscode-problemsWarningIcon-foreground: #bf8803;
--vscode-problemsInfoIcon-foreground: #1a85ff;
--vscode-minimap-findMatchHighlight: #d18616;
--vscode-minimap-selectionOccurrenceHighlight: #c9c9c9;
--vscode-minimap-selectionHighlight: #add6ff;
--vscode-minimap-infoHighlight: #1a85ff;
--vscode-minimap-warningHighlight: #bf8803;
--vscode-minimap-errorHighlight: rgba(255, 18, 18, 0.7);
--vscode-minimap-foregroundOpacity: #000000;
--vscode-minimapSlider-background: rgba(100, 100, 100, 0.2);
--vscode-minimapSlider-hoverBackground: rgba(100, 100, 100, 0.35);
--vscode-minimapSlider-activeBackground: rgba(0, 0, 0, 0.3);
--vscode-charts-foreground: #616161;
--vscode-charts-lines: rgba(97, 97, 97, 0.5);
--vscode-charts-red: #e51400;
--vscode-charts-blue: #1a85ff;
--vscode-charts-yellow: #bf8803;
--vscode-charts-orange: #d18616;
--vscode-charts-green: #388a34;
--vscode-charts-purple: #652d90;
--vscode-input-background: #ffffff;
--vscode-input-foreground: #616161;
--vscode-inputOption-activeBorder: #007acc;
--vscode-inputOption-hoverBackground: rgba(184, 184, 184, 0.31);
--vscode-inputOption-activeBackground: rgba(0, 144, 241, 0.2);
--vscode-inputOption-activeForeground: #000000;
--vscode-input-placeholderForeground: rgba(97, 97, 97, 0.5);
--vscode-inputValidation-infoBackground: #d6ecf2;
--vscode-inputValidation-infoBorder: #007acc;
--vscode-inputValidation-warningBackground: #f6f5d2;
--vscode-inputValidation-warningBorder: #b89500;
--vscode-inputValidation-errorBackground: #f2dede;
--vscode-inputValidation-errorBorder: #be1100;
--vscode-dropdown-background: #ffffff;
--vscode-dropdown-foreground: #616161;
--vscode-dropdown-border: #cecece;
--vscode-button-foreground: #ffffff;
--vscode-button-separator: rgba(255, 255, 255, 0.4);
--vscode-button-background: #007acc;
--vscode-button-hoverBackground: #0062a3;
--vscode-button-secondaryForeground: #ffffff;
--vscode-button-secondaryBackground: #5f6a79;
--vscode-button-secondaryHoverBackground: #4c5561;
--vscode-radio-activeForeground: #000000;
--vscode-radio-activeBackground: rgba(0, 144, 241, 0.2);
--vscode-radio-activeBorder: #007acc;
--vscode-radio-inactiveBorder: rgba(0, 0, 0, 0.2);
--vscode-radio-inactiveHoverBackground: rgba(184, 184, 184, 0.31);
--vscode-checkbox-background: #ffffff;
--vscode-checkbox-selectBackground: #f3f3f3;
--vscode-checkbox-foreground: #616161;
--vscode-checkbox-border: #cecece;
--vscode-checkbox-selectBorder: #424242;
--vscode-keybindingLabel-background: rgba(221, 221, 221, 0.4);
--vscode-keybindingLabel-foreground: #555555;
--vscode-keybindingLabel-border: rgba(204, 204, 204, 0.4);
--vscode-keybindingLabel-bottomBorder: rgba(187, 187, 187, 0.4);
--vscode-list-focusOutline: #0090f1;
--vscode-list-activeSelectionBackground: #0060c0;
--vscode-list-activeSelectionForeground: #ffffff;
--vscode-list-inactiveSelectionBackground: #e4e6f1;
--vscode-list-hoverBackground: #f0f0f0;
--vscode-list-dropBackground: #d6ebff;
--vscode-list-dropBetweenBackground: #424242;
--vscode-list-highlightForeground: #0066bf;
--vscode-list-focusHighlightForeground: #bbe7ff;
--vscode-list-invalidItemForeground: #b89500;
--vscode-list-errorForeground: #b01011;
--vscode-list-warningForeground: #855f00;
--vscode-listFilterWidget-background: #f3f3f3;
--vscode-listFilterWidget-outline: rgba(0, 0, 0, 0);
--vscode-listFilterWidget-noMatchesOutline: #be1100;
--vscode-listFilterWidget-shadow: rgba(0, 0, 0, 0.16);
--vscode-list-filterMatchBackground: rgba(234, 92, 0, 0.33);
--vscode-list-deemphasizedForeground: #8e8e90;
--vscode-tree-indentGuidesStroke: #a9a9a9;
--vscode-tree-inactiveIndentGuidesStroke: rgba(169, 169, 169, 0.4);
--vscode-tree-tableColumnsBorder: rgba(97, 97, 97, 0.13);
--vscode-tree-tableOddRowsBackground: rgba(97, 97, 97, 0.04);
--vscode-editorActionList-background: #f3f3f3;
--vscode-editorActionList-foreground: #616161;
--vscode-editorActionList-focusForeground: #ffffff;
--vscode-editorActionList-focusBackground: #0060c0;
--vscode-menu-foreground: #616161;
--vscode-menu-background: #ffffff;
--vscode-menu-selectionForeground: #ffffff;
--vscode-menu-selectionBackground: #0060c0;
--vscode-menu-separatorBackground: #d4d4d4;
--vscode-quickInput-background: #f3f3f3;
--vscode-quickInput-foreground: #616161;
--vscode-quickInputTitle-background: rgba(0, 0, 0, 0.06);
--vscode-pickerGroup-foreground: #0066bf;
--vscode-pickerGroup-border: #cccedb;
--vscode-quickInputList-focusForeground: #ffffff;
--vscode-quickInputList-focusBackground: #0060c0;
--vscode-search-resultsInfoForeground: #616161;
--vscode-searchEditor-findMatchBackground: rgba(234, 92, 0, 0.22);
--vscode-editor-lineHighlightBorder: #eeeeee;
--vscode-editor-rangeHighlightBackground: rgba(253, 255, 0, 0.2);
--vscode-editor-symbolHighlightBackground: rgba(234, 92, 0, 0.33);
--vscode-editorCursor-foreground: #000000;
--vscode-editorMultiCursor-primary-foreground: #000000;
--vscode-editorMultiCursor-secondary-foreground: #000000;
--vscode-editorWhitespace-foreground: rgba(51, 51, 51, 0.2);
--vscode-editorLineNumber-foreground: #237893;
--vscode-editorIndentGuide-background: rgba(51, 51, 51, 0.2);
--vscode-editorIndentGuide-activeBackground: rgba(51, 51, 51, 0.2);
--vscode-editorIndentGuide-background1: #d3d3d3;
--vscode-editorIndentGuide-background2: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-background3: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-background4: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-background5: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-background6: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-activeBackground1: #939393;
--vscode-editorIndentGuide-activeBackground2: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-activeBackground3: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-activeBackground4: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-activeBackground5: rgba(0, 0, 0, 0);
--vscode-editorIndentGuide-activeBackground6: rgba(0, 0, 0, 0);
--vscode-editorActiveLineNumber-foreground: #0b216f;
--vscode-editorLineNumber-activeForeground: #0b216f;
--vscode-editorRuler-foreground: #d3d3d3;
--vscode-editorCodeLens-foreground: #919191;
--vscode-editorBracketMatch-background: rgba(0, 100, 0, 0.1);
--vscode-editorBracketMatch-border: #b9b9b9;
--vscode-editorOverviewRuler-border: rgba(127, 127, 127, 0.3);
--vscode-editorGutter-background: #fffffe;
--vscode-editorUnnecessaryCode-opacity: rgba(0, 0, 0, 0.47);
--vscode-editorGhostText-foreground: rgba(0, 0, 0, 0.47);
--vscode-editorOverviewRuler-rangeHighlightForeground: rgba(0, 122, 204, 0.6);
--vscode-editorOverviewRuler-errorForeground: rgba(255, 18, 18, 0.7);
--vscode-editorOverviewRuler-warningForeground: #bf8803;
--vscode-editorOverviewRuler-infoForeground: #1a85ff;
--vscode-editorBracketHighlight-foreground1: #0431fa;
--vscode-editorBracketHighlight-foreground2: #319331;
--vscode-editorBracketHighlight-foreground3: #7b3814;
--vscode-editorBracketHighlight-foreground4: rgba(0, 0, 0, 0);
--vscode-editorBracketHighlight-foreground5: rgba(0, 0, 0, 0);
--vscode-editorBracketHighlight-foreground6: rgba(0, 0, 0, 0);
--vscode-editorBracketHighlight-unexpectedBracket-foreground: rgba(255, 18, 18, 0.8);
--vscode-editorBracketPairGuide-background1: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-background2: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-background3: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-background4: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-background5: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-background6: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-activeBackground1: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-activeBackground2: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-activeBackground3: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-activeBackground4: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-activeBackground5: rgba(0, 0, 0, 0);
--vscode-editorBracketPairGuide-activeBackground6: rgba(0, 0, 0, 0);
--vscode-editorUnicodeHighlight-border: #bf8803;
--vscode-diffEditor-move-border: rgba(139, 139, 139, 0.61);
--vscode-diffEditor-moveActive-border: #ffa500;
--vscode-diffEditor-unchangedRegionShadow: rgba(115, 115, 115, 0.75);
--vscode-multiDiffEditor-background: #fffffe;
--vscode-multiDiffEditor-border: #cccccc;
--vscode-editorOverviewRuler-bracketMatchForeground: #a0a0a0;
--vscode-symbolIcon-arrayForeground: #616161;
--vscode-symbolIcon-booleanForeground: #616161;
--vscode-symbolIcon-classForeground: #d67e00;
--vscode-symbolIcon-colorForeground: #616161;
--vscode-symbolIcon-constantForeground: #616161;
--vscode-symbolIcon-constructorForeground: #652d90;
--vscode-symbolIcon-enumeratorForeground: #d67e00;
--vscode-symbolIcon-enumeratorMemberForeground: #007acc;
--vscode-symbolIcon-eventForeground: #d67e00;
--vscode-symbolIcon-fieldForeground: #007acc;
--vscode-symbolIcon-fileForeground: #616161;
--vscode-symbolIcon-folderForeground: #616161;
--vscode-symbolIcon-functionForeground: #652d90;
--vscode-symbolIcon-interfaceForeground: #007acc;
--vscode-symbolIcon-keyForeground: #616161;
--vscode-symbolIcon-keywordForeground: #616161;
--vscode-symbolIcon-methodForeground: #652d90;
--vscode-symbolIcon-moduleForeground: #616161;
--vscode-symbolIcon-namespaceForeground: #616161;
--vscode-symbolIcon-nullForeground: #616161;
--vscode-symbolIcon-numberForeground: #616161;
--vscode-symbolIcon-objectForeground: #616161;
--vscode-symbolIcon-operatorForeground: #616161;
--vscode-symbolIcon-packageForeground: #616161;
--vscode-symbolIcon-propertyForeground: #616161;
--vscode-symbolIcon-referenceForeground: #616161;
--vscode-symbolIcon-snippetForeground: #616161;
--vscode-symbolIcon-stringForeground: #616161;
--vscode-symbolIcon-structForeground: #616161;
--vscode-symbolIcon-textForeground: #616161;
--vscode-symbolIcon-typeParameterForeground: #616161;
--vscode-symbolIcon-unitForeground: #616161;
--vscode-symbolIcon-variableForeground: #007acc;
--vscode-actionBar-toggledBackground: rgba(0, 144, 241, 0.2);
--vscode-peekViewTitle-background: #f3f3f3;
--vscode-peekViewTitleLabel-foreground: #000000;
--vscode-peekViewTitleDescription-foreground: #616161;
--vscode-peekView-border: #1a85ff;
--vscode-peekViewResult-background: #f3f3f3;
--vscode-peekViewResult-lineForeground: #646465;
--vscode-peekViewResult-fileForeground: #1e1e1e;
--vscode-peekViewResult-selectionBackground: rgba(51, 153, 255, 0.2);
--vscode-peekViewResult-selectionForeground: #6c6c6c;
--vscode-peekViewEditor-background: #f2f8fc;
--vscode-peekViewEditorGutter-background: #f2f8fc;
--vscode-peekViewEditorStickyScroll-background: #f2f8fc;
--vscode-peekViewResult-matchHighlightBackground: rgba(234, 92, 0, 0.3);
--vscode-peekViewEditor-matchHighlightBackground: rgba(245, 216, 2, 0.87);
--vscode-editor-foldBackground: rgba(173, 214, 255, 0.3);
--vscode-editor-foldPlaceholderForeground: #808080;
--vscode-editorGutter-foldingControlForeground: #424242;
--vscode-editorSuggestWidget-background: #f3f3f3;
--vscode-editorSuggestWidget-border: #c8c8c8;
--vscode-editorSuggestWidget-foreground: #000000;
--vscode-editorSuggestWidget-selectedForeground: #ffffff;
--vscode-editorSuggestWidget-selectedBackground: #0060c0;
--vscode-editorSuggestWidget-highlightForeground: #0066bf;
--vscode-editorSuggestWidget-focusHighlightForeground: #bbe7ff;
--vscode-editorSuggestWidgetStatus-foreground: rgba(0, 0, 0, 0.5);
--vscode-editorMarkerNavigationError-background: #e51400;
--vscode-editorMarkerNavigationError-headerBackground: rgba(229, 20, 0, 0.1);
--vscode-editorMarkerNavigationWarning-background: #bf8803;
--vscode-editorMarkerNavigationWarning-headerBackground: rgba(191, 136, 3, 0.1);
--vscode-editorMarkerNavigationInfo-background: #1a85ff;
--vscode-editorMarkerNavigationInfo-headerBackground: rgba(26, 133, 255, 0.1);
--vscode-editorMarkerNavigation-background: #fffffe;
--vscode-editor-linkedEditingBackground: rgba(255, 0, 0, 0.3);
--vscode-editor-wordHighlightBackground: rgba(87, 87, 87, 0.25);
--vscode-editor-wordHighlightStrongBackground: rgba(14, 99, 156, 0.25);
--vscode-editor-wordHighlightTextBackground: rgba(87, 87, 87, 0.25);
--vscode-editorOverviewRuler-wordHighlightForeground: rgba(160, 160, 160, 0.8);
--vscode-editorOverviewRuler-wordHighlightStrongForeground: rgba(192, 160, 192, 0.8);
--vscode-editorOverviewRuler-wordHighlightTextForeground: rgba(160, 160, 160, 0.8);
--vscode-editorHoverWidget-highlightForeground: #0066bf;
--vscode-editor-placeholder-foreground: rgba(0, 0, 0, 0.47); }

.mtk1 { color: #000000; }
.mtk2 { color: #fffffe; }
.mtk3 { color: #808080; }
.mtk4 { color: #ff0000; }
.mtk5 { color: #0451a5; }
.mtk6 { color: #0000ff; }
.mtk7 { color: #098658; }
.mtk8 { color: #008000; }
.mtk9 { color: #dd0000; }
.mtk10 { color: #383838; }
.mtk11 { color: #cd3131; }
.mtk12 { color: #863b00; }
.mtk13 { color: #af00db; }
.mtk14 { color: #800000; }
.mtk15 { color: #e00000; }
.mtk16 { color: #3030c0; }
.mtk17 { color: #666666; }
.mtk18 { color: #778899; }
.mtk19 { color: #c700c7; }
.mtk20 { color: #a31515; }
.mtk21 { color: #4f76ac; }
.mtk22 { color: #008080; }
.mtk23 { color: #001188; }
.mtk24 { color: #4864aa; }
.mtki { font-style: italic; }
.mtkb { font-weight: bold; }
.mtku { text-decoration: underline; text-underline-position: under; }
.mtks { text-decoration: line-through; }
.mtks.mtku { text-decoration: underline line-through; text-underline-position: under; }</style></head>

  <!-- Google tag (gtag.js) -->
  
  

  <body class="enable-motion underline-links" style="cursor: default;">

    <header>
        <div id="menu-items">
            <div><a href="https://markdownlivepreview.com/">Markdown Live Preview</a></div>
            <div id="reset-button"><a href="https://markdownlivepreview.com/#">Reset</a></div>
            <div id="copy-button"><a href="https://markdownlivepreview.com/#">Copy</a></div>
            <div id="sync-button"><input type="checkbox" id="sync-scroll-checkbox"><label for="sync-scroll-checkbox">Sync scroll</label></div>
        </div>
        <div id="github"><a href="https://github.com/tanabe/markdown-live-preview"><img src="./Readme_files/GitHub-Mark-Light-32px.webp"></a></div>
    </header>

    <div id="container" class="split-container">

        <div id="edit" class="column editor-pane" style="width: 661px;">
            <div id="editor-wrapper">
                <div id="editor" data-keybinding-context="1" data-mode-id="markdown" style="--vscode-editorCodeLens-lineHeight: 16px; --vscode-editorCodeLens-fontSize: 12px; --vscode-editorCodeLens-fontFeatureSettings: &quot;liga&quot; off, &quot;calt&quot; off;"><div class="monaco-editor no-user-select  showUnused showDeprecated vs focused" role="code" data-uri="inmemory://model/1" style="width: 661px; height: 585px;"><div data-mprt="3" class="overflow-guard" style="width: 661px; height: 585px;"><div class="margin" role="presentation" aria-hidden="true" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: -1526px; height: 2166px; width: 48px;"><div class="glyph-margin" style="left: 0px; width: 0px; height: 2166px;"></div><div class="margin-view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="margin-view-overlays focused" role="presentation" aria-hidden="true" style="position: absolute; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; font-variation-settings: normal; line-height: 19px; letter-spacing: 0px; width: 48px; height: 2185px;"><div style="top:1520px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">76</div></div><div style="top:1539px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">77</div></div><div style="top:1558px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">78</div></div><div style="top:1577px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">79</div></div><div style="top:1596px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">80</div></div><div style="top:1615px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">81</div></div><div style="top:1634px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">82</div></div><div style="top:1653px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">83</div></div><div style="top:1672px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">84</div></div><div style="top:1691px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">85</div></div><div style="top:1710px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">86</div></div><div style="top:1729px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">87</div></div><div style="top:1748px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">88</div></div><div style="top:1767px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">89</div></div><div style="top:1786px;height:19px;"><div class="current-line current-line-margin-both" style="width:48px"></div><div class="line-numbers active-line-number" style="left:0px;width:38px;">90</div></div><div style="top:1805px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">91</div></div><div style="top:1824px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">92</div></div><div style="top:1843px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">93</div></div><div style="top:1862px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">94</div></div><div style="top:1881px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">95</div></div><div style="top:1900px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">96</div></div><div style="top:1919px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">97</div></div><div style="top:1938px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">98</div></div><div style="top:1976px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">100</div></div><div style="top:1995px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">101</div></div><div style="top:2014px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">102</div></div><div style="top:2033px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">103</div></div><div style="top:2052px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">104</div></div><div style="top:2071px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">105</div></div><div style="top:2090px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">106</div></div><div style="top:2109px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">107</div></div><div style="top:1957px;height:19px;"><div class="line-numbers" style="left:0px;width:38px;">99</div></div></div><div class="glyph-margin-widgets" style="position: absolute; top: 0px;"></div></div><div class="monaco-scrollable-element editor-scrollable vs" role="presentation" data-mprt="6" style="position: absolute; overflow: hidden; left: 48px; width: 613px; height: 585px;"><div class="lines-content monaco-editor-background" style="position: absolute; overflow: hidden; width: 1.67772e+07px; height: 1.67772e+07px; transform: translate3d(0px, 0px, 0px); contain: strict; top: -1526px; left: 0px;"><div class="view-overlays focused" role="presentation" aria-hidden="true" style="position: absolute; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; font-variation-settings: normal; line-height: 19px; letter-spacing: 0px; height: 0px; width: 613px;"><div style="top:1520px;height:19px;"></div><div style="top:1539px;height:19px;"></div><div style="top:1558px;height:19px;"></div><div style="top:1577px;height:19px;"></div><div style="top:1596px;height:19px;"></div><div style="top:1615px;height:19px;"></div><div style="top:1634px;height:19px;"></div><div style="top:1653px;height:19px;"></div><div style="top:1672px;height:19px;"></div><div style="top:1691px;height:19px;"></div><div style="top:1710px;height:19px;"></div><div style="top:1729px;height:19px;"></div><div style="top:1748px;height:19px;"></div><div style="top:1767px;height:19px;"></div><div style="top:1786px;height:19px;"><div class="current-line current-line-exact" style="width:613px;"></div><div class="cdr wordHighlightText" style="left:246px;width:38px;"></div></div><div style="top:1805px;height:19px;"></div><div style="top:1824px;height:19px;"></div><div style="top:1843px;height:19px;"></div><div style="top:1862px;height:19px;"></div><div style="top:1881px;height:19px;"></div><div style="top:1900px;height:19px;"></div><div style="top:1919px;height:19px;"></div><div style="top:1938px;height:19px;"></div><div style="top: 1976px; height: 19px;"></div><div style="top: 1995px; height: 19px;"></div><div style="top: 2014px; height: 19px;"></div><div style="top: 2033px; height: 19px;"></div><div style="top: 2052px; height: 19px;"></div><div style="top: 2071px; height: 19px;"></div><div style="top: 2090px; height: 19px;"></div><div style="top: 2109px; height: 19px;"></div><div style="top:1957px;height:19px;"></div></div><div role="presentation" aria-hidden="true" class="view-rulers"></div><div class="view-zones" role="presentation" aria-hidden="true" style="position: absolute;"></div><div class="view-lines monaco-mouse-cursor-text" role="presentation" aria-hidden="true" data-mprt="8" style="position: absolute; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; font-variation-settings: normal; line-height: 19px; letter-spacing: 0px; width: 613px; height: 2185px;"><div style="top:1520px;height:19px;" class="view-line"><span><span class="mtk6">---</span></span></div><div style="top:1539px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1558px;height:19px;" class="view-line"><span><span class="mtk6">##&nbsp;💡&nbsp;Key&nbsp;Insights</span></span></div><div style="top:1577px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1596px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1">Long-term&nbsp;contracts&nbsp;and&nbsp;credit&nbsp;card&nbsp;payments&nbsp;reduc</span><span class="mtk1">e&nbsp;churn</span></span></div><div style="top:1615px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1">Fiber&nbsp;optic&nbsp;users&nbsp;show&nbsp;higher&nbsp;churn&nbsp;rates</span></span></div><div style="top:1634px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1">Bundled&nbsp;services&nbsp;</span><span class="mtk1 bracket-highlighting-0">(</span><span class="mtk1">security,&nbsp;streaming</span><span class="mtk1 bracket-highlighting-0">)</span><span class="mtk1">&nbsp;improve&nbsp;retention</span></span></div><div style="top:1653px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1">Competitor-driven&nbsp;churn&nbsp;dominates—pricing&nbsp;and&nbsp;</span><span class="mtk1">loyalty&nbsp;programs&nbsp;needed</span></span></div><div style="top:1672px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1691px;height:19px;" class="view-line"><span><span class="mtk6">---</span></span></div><div style="top:1710px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1729px;height:19px;" class="view-line"><span><span class="mtk6">##&nbsp;🧰&nbsp;Tech&nbsp;Stack</span></span></div><div style="top:1748px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1767px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1 mtkb">**Languages**</span><span class="mtk1">:&nbsp;Python,&nbsp;SQL</span></span></div><div style="top:1786px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1 mtkb">**Libraries**</span><span class="mtk1">:&nbsp;Pandas,&nbsp;Scikit-learn</span></span></div><div style="top:1805px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1 mtkb">**Tools**</span><span class="mtk1">:&nbsp;Power&nbsp;BI,&nbsp;SQL&nbsp;Server</span></span></div><div style="top:1824px;height:19px;" class="view-line"><span><span class="mtk6">-&nbsp;</span><span class="mtk1 mtkb">**Model**</span><span class="mtk1">:&nbsp;Random&nbsp;Forest</span></span></div><div style="top:1843px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1862px;height:19px;" class="view-line"><span><span class="mtk6">---</span></span></div><div style="top:1881px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1900px;height:19px;" class="view-line"><span><span class="mtk6">##&nbsp;Screenshots</span></span></div><div style="top:1919px;height:19px;" class="view-line"><span><span></span></span></div><div style="top:1938px;height:19px;" class="view-line"><span><span class="mtk20">![</span><span class="mtk1">Screenshot</span><span class="mtk20">](https://via.placeholder.com/468x300?text=App+Scr</span><span class="mtk20">eenshot+Here)</span></span></div><div style="top: 1976px; height: 19px;" class="view-line"><span><span></span></span></div><div style="top: 1995px; height: 19px;" class="view-line"><span><span class="mtk6">---</span></span></div><div style="top: 2014px; height: 19px;" class="view-line"><span><span></span></span></div><div style="top: 2033px; height: 19px;" class="view-line"><span><span class="mtk6">##&nbsp;🛠️&nbsp;Installation&nbsp;&amp;&nbsp;Usage</span></span></div><div style="top: 2052px; height: 19px;" class="view-line"><span><span></span></span></div><div style="top: 2071px; height: 19px;" class="view-line"><span><span class="mtk6">###&nbsp;Clone&nbsp;the&nbsp;Repository</span></span></div><div style="top: 2090px; height: 19px;" class="view-line"><span><span></span></span></div><div style="top: 2109px; height: 19px;" class="view-line"><span><span class="mtk20">```bash</span></span></div><div style="top:1957px;height:19px;" class="view-line"><span><span class="mtk20">![</span><span class="mtk1">Screenshot</span><span class="mtk20">](https://via.placeholder.com/468x300?text=App+Scr</span><span class="mtk20">eenshot+Here)</span></span></div></div><div data-mprt="1" class="contentWidgets" style="position: absolute; top: 0px;"></div><div role="presentation" aria-hidden="true" class="cursors-layer cursor-line-style cursor-solid"><div class="cursor  monaco-mouse-cursor-text " style="height: 19px; top: 1786px; left: 284px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; font-variation-settings: normal; line-height: 19px; letter-spacing: 0px; display: block; visibility: hidden; padding-left: 1px; width: 2px;"></div></div></div><div role="presentation" aria-hidden="true" class="invisible scrollbar horizontal" style="position: absolute; width: 599px; height: 12px; left: 0px; bottom: 0px;"><div class="slider" style="position: absolute; top: 0px; left: 0px; height: 12px; transform: translate3d(0px, 0px, 0px); contain: strict; width: 599px;"></div></div><canvas class="decorationsOverviewRuler" aria-hidden="true" width="14" height="585" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; top: 0px; right: 0px; width: 14px; height: 585px; display: block;"></canvas><div role="presentation" aria-hidden="true" class="visible scrollbar vertical" style="position: absolute; width: 14px; height: 585px; right: 0px; top: 0px;"><div class="slider" style="position: absolute; top: 409px; left: 0px; width: 14px; transform: translate3d(0px, 0px, 0px); contain: strict; height: 156px;"></div></div></div><div role="presentation" aria-hidden="true" style="width: 661px;" class="scroll-decoration"></div><textarea data-mprt="7" class="inputarea monaco-mouse-cursor-text" wrap="on" autocorrect="off" autocapitalize="off" autocomplete="off" spellcheck="false" aria-label="Editor content" aria-required="false" tabindex="0" role="textbox" aria-roledescription="editor" aria-multiline="true" aria-autocomplete="both" style="tab-size: 15.3984px; font-family: Consolas, &quot;Courier New&quot;, monospace; font-weight: normal; font-size: 14px; font-feature-settings: &quot;liga&quot; 0, &quot;calt&quot; 0; font-variation-settings: normal; line-height: 19px; letter-spacing: 0px; top: 260px; left: 48px; width: 593px; height: 1px;"></textarea><div style="position: absolute; top: 0px; left: 0px; width: 0px; height: 0px;" class="monaco-editor-background textAreaCover line-numbers"></div><div data-mprt="4" class="overlayWidgets" style="width: 661px;"><div class="sticky-widget" widgetid="editor.contrib.stickyScrollWidget" style="width: 647px; position: absolute; right: 50%; top: 0px; display: none;"><div class="sticky-widget-line-numbers" role="none" style="width: 48px;"></div><div class="sticky-widget-lines-scrollable" style="--vscode-editorStickyScroll-scrollableWidth: 599px;"><div class="sticky-widget-lines" role="list" style="left: 0px;"></div></div></div><div class="monaco-hover hidden" tabindex="0" role="tooltip" widgetid="editor.contrib.modesGlyphHoverWidget" style="position: absolute;"><div class="monaco-scrollable-element " role="presentation" style="position: relative; overflow: hidden;"><div class="monaco-hover-content" style="overflow: hidden;"></div><div role="presentation" aria-hidden="true" class="invisible scrollbar horizontal" style="position: absolute;"><div class="slider" style="position: absolute; top: 0px; left: 0px; height: 10px; transform: translate3d(0px, 0px, 0px); contain: strict;"></div></div><div role="presentation" aria-hidden="true" class="invisible scrollbar vertical" style="position: absolute;"><div class="slider" style="position: absolute; top: 0px; left: 0px; width: 10px; transform: translate3d(0px, 0px, 0px); contain: strict;"></div></div><div class="shadow"></div><div class="shadow"></div><div class="shadow"></div></div></div></div><div data-mprt="9" class="minimap slider-mouseover" role="presentation" aria-hidden="true" style="position: absolute; left: 0px; width: 0px; height: 585px;"><div class="minimap-shadow-hidden" style="height: 585px;"></div><canvas width="0" height="585" style="position: absolute; left: 0px; width: 0px; height: 585px;"></canvas><canvas class="minimap-decorations-layer" width="0" height="585" style="position: absolute; left: 0px; width: 0px; height: 585px;"></canvas><div class="minimap-slider" style="position: absolute; transform: translate3d(0px, 0px, 0px); contain: strict; width: 0px;"><div class="minimap-slider-horizontal" style="position: absolute; width: 0px; height: 0px;"></div></div></div><div role="presentation" aria-hidden="true" class="blockDecorations-container"></div></div><div data-mprt="2" class="overflowingContentWidgets"></div><div data-mprt="5" class="overflowingOverlayWidgets"></div></div><div class="context-view" aria-hidden="true" style="display: none;"></div></div>
            </div>
        </div>

        <div id="split-divider" class="split-divider"></div>

        <div id="preview" class="column preview-pane" style="width: 692px;">
            <div id="preview-wrapper">
                <div id="output" class="content markdown-body"><h1>📞 Telecom Churn Analysis &amp; Prediction</h1>
<p>This project presents a comprehensive approach to understanding and predicting customer churn in the telecom industry. It combines SQL-based ETL pipelines, Power BI dashboards for visual analytics, and Python-based machine learning models to identify at-risk customers and provide actionable business insights.</p>
<hr>
<h2>📚 Table of Contents</h2>
<ul>
<li><a href="https://markdownlivepreview.com/#project-overview">Project Overview</a></li>
<li><a href="https://markdownlivepreview.com/#etl-pipeline">ETL Pipeline</a></li>
<li><a href="https://markdownlivepreview.com/#churn-analysis-dashboard">Churn Analysis Dashboard</a></li>
<li><a href="https://markdownlivepreview.com/#churn-prediction-model">Churn Prediction Model</a></li>
<li><a href="https://markdownlivepreview.com/#prediction-dashboard">Prediction Dashboard</a></li>
<li><a href="https://markdownlivepreview.com/#key-insights">Key Insights</a></li>
<li><a href="https://markdownlivepreview.com/#tech-stack">Tech Stack</a></li>
<li><a href="https://markdownlivepreview.com/#installation--usage">Installation &amp; Usage</a></li>
<li><a href="https://markdownlivepreview.com/#screenshots">Screenshots</a></li>
</ul>
<hr>
<h2>📌 Project Overview</h2>
<p>Customer churn is a critical metric for telecom companies. This project aims to:</p>
<ul>
<li>Analyze historical churn data to uncover trends and patterns</li>
<li>Build a predictive model to identify customers likely to churn</li>
<li>Visualize insights and predictions using Power BI dashboards</li>
<li>Enable data-driven decision-making for customer retention strategies</li>
</ul>
<hr>
<h2>🔄 ETL Pipeline</h2>
<p><strong>Tools Used</strong>: SQL Server Management Studio (SSMS)</p>
<p><strong>Steps</strong>:</p>
<ol>
<li>Import raw CSV data into SQL Server</li>
<li>Clean and transform data into structured tables</li>
<li>Create views for Power BI consumption</li>
<li>Ensure data integrity and normalization</li>
</ol>
<hr>
<h2>📈 Churn Analysis Dashboard</h2>
<p>Built in Power BI, this dashboard provides:</p>
<ul>
<li>Churn rate by contract type, payment method, tenure, and internet service</li>
<li>Heatmap of churn across different states</li>
<li>Breakdown of churn categories (e.g., Competitor, Price, Dissatisfaction)</li>
<li>KPIs: Total Customers, New Joiners, Churn Rate</li>
</ul>
<hr>
<h2>🤖 Churn Prediction Model</h2>
<p><strong>Language</strong>: Python<br><strong>Algorithm</strong>: Random Forest Classifier</p>
<p><strong>Steps</strong>:</p>
<ul>
<li>Data preprocessing: Label encoding, missing value handling</li>
<li>Feature selection: Tenure, services, contract type, payment method</li>
<li>Model training and evaluation: Accuracy, precision, recall, F1-score</li>
<li>Output: Churn probability and customer risk classification</li>
</ul>
<hr>
<h2>📊 Prediction Dashboard</h2>
<p>Power BI dashboard visualizing model predictions:</p>
<ul>
<li>Total predicted churners</li>
<li>Churn distribution by gender, age group, marital status, tenure</li>
<li>Customer-level risk matrix with revenue, referrals, and refund data</li>
</ul>
<hr>
<h2>💡 Key Insights</h2>
<ul>
<li>Long-term contracts and credit card payments reduce churn</li>
<li>Fiber optic users show higher churn rates</li>
<li>Bundled services (security, streaming) improve retention</li>
<li>Competitor-driven churn dominates—pricing and loyalty programs needed</li>
</ul>
<hr>
<h2>🧰 Tech Stack</h2>
<ul>
<li><strong>Languages</strong>: Python, SQL</li>
<li><strong>Libraries</strong>: Pandas, Scikit-learn</li>
<li><strong>Tools</strong>: Power BI, SQL Server</li>
<li><strong>Model</strong>: Random Forest</li>
</ul>
<hr>
<h2>Screenshots</h2>
<p><img alt="Screenshot" src="https://via.placeholder.com/468x300?text=App+Screenshot+Here">
<img alt="Screenshot" src="https://via.placeholder.com/468x300?text=App+Screenshot+Here"></p>
<hr>
<h2>🛠️ Installation &amp; Usage</h2>
<h3>Clone the Repository</h3>
<pre><code class="language-bash">git clone https:///github.com/Lavnish-s-s/telecom-customer-churn-analysis-and-prediction.git
cd telecom-customer-churn-analysis-and-prediction
</code></pre>
</div>
            </div>
        </div>
    </div>

    <footer></footer>
  

<div class="context-view" aria-hidden="true" style="display: none;"></div><div class="monaco-aria-container"><div class="monaco-alert" role="alert" aria-atomic="true"></div><div class="monaco-alert" role="alert" aria-atomic="true"></div><div class="monaco-status" aria-live="polite" aria-atomic="true"></div><div class="monaco-status" aria-live="polite" aria-atomic="true"></div></div></body></html>