## Welcome to Byetnet.com Gits

You can use the [editor on GitHub](https://github.com/byetnetcom/Html-xml/edit/master/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

<div dir="ltr" style="text-align: left;" trbidi="on">
<div class="b-c-c">
<form>
<div style="text-align: left;">
<div style="text-align: left;">
<div style="text-align: justify;">
Html to xml. Code converter for Google, Yahoo, Taboola, Mgid Ad Code, Html code, code parse tool for blogger use it for free. This tool easily parse your code just a single click.
<h2>
Instructions:</h2>
<div>
<b>1.&nbsp;</b>Paste your code in this box below.</div>
<div>
<b>2.&nbsp;</b>Click Convert button only one time after pasting your code and your code will be converted easily.</div>
</div>
</div>
</div>
<textarea name="data1"></textarea>
<div class="b-c-b">
<input class="byet2" onclick="html2entities(this.form.data1)" onmouseout="this.className='byet2'" onmouseover="this.className='byet2 byet2hov'" type="button" value="Convert" />     <input class="byet2" onmouseout="this.className='byet2'" onmouseover="this.className='byet2 byet2hov'" type="reset" value="Clear" />
<div>
</div>
</div>
</form>
</div>
<script type="text/javascript">
        //<![CDATA[
        function html2entities(){
          var re=/[(<>"'&]/g
          for (i=0; i<arguments.length; i++)
            arguments[i].value=arguments[i].value.replace(re, function(m){return replacechar(m)})
            }
        function replacechar(match){
          if (match=="<")
            return "&lt;"
            else if (match==">")
              return "&gt;"
              else if (match=="\"")
                return "&quot;"
                else if (match=="'")
                  return "&#039;"
                  else if (match=="&")
                    return "&amp;"
                    }
//]]>
      </script> <style>
.b-c-c textarea {
    width: 100%;
    box-sizing: border-box;
    height: 500px;
}
.b-c-b {
    text-align: center;
}
.b-c-b .byet2 {
    background: #e74c3c;
    padding: 8px 12px;
    color: #ffffff;
    border: 3%;border-color:e74c3c;
text-transform:uppercase;
cursor:pointer;
}
.b-c-b .byet2:hover {
background:#ffffff; color:#000000;
}

</style> </div>
