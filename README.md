# How-to-hide-Top-Side-Bard-of-Sharepoint-2010
hide Top and Side Bar of Sharepoint 2010

1) open edit menu
2) add Content **Editor Web Part** ( Web Part > Media and Content > Content Editor )
3) click on the new content editor web part you made and click on the small down arrow on the right side of the web form and click **edit Web Part**
4) Then in the Content Editor web part click on the text saying **Click here to add new content**
5) In the editor menu click **Format Text**
6) on the far right field click **HTML > Edit HTML Source**
7) in the box that pops up pase this code 

``<style type="text/css">
    #s4-ribbonrow, .ms-cui-topBar2, .s4-notdlg, .s4-pr s4-ribbonrowhidetitle, .s4-notdlg noindex, #ms-cui-ribbonTopBars, #s4-titlerow, #s4-pr s4-notdlg s4-titlerowhidetitle, #s4-leftpanel-content {display:none !important;}
    .s4-ca{margin-left:0px !important; margin-right:0px !important;}
</style>``
