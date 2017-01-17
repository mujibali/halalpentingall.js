<script type='text/javascript'>
//<![CDATA[
function bp_thumbnail_resize(e,d){var c=275;var a=true;var b="http://2.bp.blogspot.com/-erTXCq61ULM/TmHYAQBZ0GI/AAAAAAAACCs/6cBX54Dn6Gs/s72-c/default.png";if(a==true&&e==""){e=b}image_tag='<img src="'+e.replace("/s72-c/","/s"+c+"-c/")+'" class="postthumb" alt="'+d+'"/>';if(e!=""){return image_tag}else{return""}};
//]]>
</script>
<a expr:href='data:post.url'><script type='text/javascript'>
document.write(bp_thumbnail_resize(&quot;<data:post.thumbnailUrl/>&quot;,&quot;<data:post.title/>&quot;));
</script></a>
</div>
</b:if></b:if>

    <div class='post-header'>
    <div class='post-header-line-1'/>
    </div>

    <div class='post-body entry-content' expr:id='&quot;post-body-&quot; + data:post.id'>
<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
  <div expr:id='&quot;summary&quot; + data:post.id'><p><data:post.body/></p></div>
<script type='text/javascript'>createSummaryAndThumb(&quot;summary<data:post.id/>&quot;);</script>

<b:if cond='data:blog.url == data:blog.homepageUrl'> 
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<div class='postmeta'>
		
<span class='comments-tab' id='fb-comments' onclick='javascript:commentToggle(&quot;#fb-comments&quot;);' title='Comments made with Facebook'><img class='comments-tab-icon' height='20px' src='https://3.bp.blogspot.com/-HpLRb39CySM/WGsFgTrqxcI/AAAAAAAAB5M/ZvtgcJub2-kjZsOrqhyPhgeT3Zxvcm7JgCLcB/s1600/1458600807289.JPEG' width='20px'/><fb:comments-count expr:href='data:post.url'/><span><i aria-hidden='true' class='fa fa-comments'/></span></span>
<script async='async' data-cfasync='false' defer='defer' src='http://connect.facebook.net/en_US/all.js#xfbml=1'/>
<script async='async' data-cfasync='false' defer='defer' src='http://code.jquery.com/jquery-latest.js'/><meta content='100000582070970' property='fb:admins'/><script type='text/javascript'>
/* contents of a small JavaScript file*/
function commentToggle(selectTab) {$(&quot;.comments-tab&quot;).addClass(&quot;inactive-select-tab&quot;);$(selectTab).removeClass(&quot;inactive-select-tab&quot;);$(&quot;.comments-page&quot;).hide();$(selectTab + &quot;-page&quot;).show();}</script>
  <span class='numcomment'><span><img alt='Komentar' height='15px' src='http://www.blogger.com/img/icon_logo32.gif' width='15px'/><data:post.numComments/><span><i aria-hidden='true' class='fa fa-comments'/></span></span></span>
  </div>
</b:if>
</b:if>

</b:if>
</b:if>

      <b:if cond='data:blog.pageType == &quot;item&quot;'>

<b:if cond='data:blog.pageType == &quot;item&quot;'>
<b:if cond='data:post.snippet'>
<meta expr:content='data:post.snippet' name='description'/>
</b:if>
</b:if>

        <p><div expr:id='&quot;post1&quot; + data:post.id'/>
<div class='post-terkait'>
<b:if cond='data:post.labels'>
<b:loop values='data:post.labels' var='label'>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<script expr:src='&quot;/feeds/posts/default/-/&quot; + data:label.name + &quot;?alt=json-in-script&amp;callback=related_results_labels&amp;max-results=3&quot;' type='text/javascript'/>
</b:if>
</b:loop>
</b:if>
<h4>Baca Juga</h4>
<script type='text/javascript'>
removeRelatedDuplicates();
printRelatedLabels();
</script>
</div>
<div class='artbody' expr:id='&quot;post2&quot; + data:post.id' itemprop='articleBody description'><data:post.body/></div>
<script type='text/javascript'>
var obj0=document.getElementById(&quot;post1<data:post.id/>&quot;);
var obj1=document.getElementById(&quot;post2<data:post.id/>&quot;);
var s=obj1.innerHTML;
var t=s.substr(0,s.length/3);
var r=t.lastIndexOf(&quot;&lt;br&gt;&quot;);
if(r&gt;0) {obj0.innerHTML=s.substr(0,r);obj1.innerHTML=s.substr(r+4);}
</script>
</p></b:if>
      <b:if cond='data:blog.pageType == &quot;static_page&quot;'>
<p><data:post.body/></p>
</b:if>
      <div style='clear: both;'/> <!-- clear for photos floats -->
    </div>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<!-- Scripts Start -->
<b:if cond='data:post.isFirstPost'>
<!-- Facebook -->
<div id='fb-root'/>
<script>(function(d, s, id) {
var js, fjs = d.getElementsByTagName(s)[0];
if (d.getElementById(id)) {return;}
js = d.createElement(s); js.id = id;
js.src = &quot;http://connect.facebook.net/en_US/all.js#xfbml=1&quot;;
fjs.parentNode.insertBefore(js, fjs);
}(document, &#39;script&#39;, &#39;facebook-jssdk&#39;));
</script>
<!-- Google +1 -->
<script type='text/javascript'>
(function() {
var po = document.createElement(&#39;script&#39;); po.type = &#39;text/javascript&#39;; po.async = true;
po.src = &#39;https://apis.google.com/js/plusone.js&#39;;
var s = document.getElementsByTagName(&#39;script&#39;)[0]; s.parentNode.insertBefore(po, s);
})();
</script>
<!-- Twitter -->
<script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0];if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=&quot;//platform.twitter.com/widgets.js&quot;;fjs.parentNode.insertBefore(js,fjs);}}(document,&quot;script&quot;,&quot;twitter-wjs&quot;);</script>
</b:if>
<!-- Scripts End -->
<!-- Horizontal social buttons Start -->
<span style='font-family: &quot;courier new&quot; , &quot;courier&quot; , monospace; font-size: x-small;'><b>Bagikan Artikel Ini :</b></span>
<div class='horizontal-social-buttons' style='padding:10px 0 10px;'>
<!-- Twitter -->
<div style='float:left;'>
<a class='twitter-share-button' data-count='horizontal' data-lang='en' data-related='' data-via='' expr:data-text='data:post.title' expr:data-url='data:post.url' href='https://twitter.com/share'>Tweet</a>
</div>
<!-- Google +1 -->
<div style='float:left;'>
<g:plusone annotation='bubble' expr:href='data:post.url' size='medium'/>
</div>
<!-- Facebook Like+Send -->
<div style='float:left;'>
<fb:like colorscheme='light' expr:href='data:post.url' font='' layout='button_count' send='true' show_faces='false'/>
</div>
<!-- Pinterest Start -->
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<div id='pin-wrapper' style='float: left; margin:0px 0px 0px 30px; width:44px;'>
<a data-pin-config='beside' data-pin-do='buttonPin' expr:href='&quot;http://pinterest.com/pin/create/button/?url=&quot; + data:post.url'><img src='//assets.pinterest.com/images/pidgets/pin_it_button.png'/></a>
<span style='margin-left:-44px;'><a data-pin-config='beside' data-pin-do='buttonBookmark' href='//pinterest.com/pin/create/button/' style='outline:none;border:none;'/></span>
</div> 
<script src='http://assets.pinterest.com/js/pinit.js' type='text/javascript'/>
<style type='text/css'> 
#pin-wrapper &gt; a {background-image:none !important;}
</style> 
</b:if> 
<!-- Pinterest End -->
<!-- Whatsapp Share Buttons Start -->
<script type='text/javascript'>if(typeof wabtn4fg===&quot;undefined&quot;){wabtn4fg=1;h=document.head||document.getElementsByTagName(&quot;head&quot;)[0],s=document.createElement(&quot;script&quot;);s.type=&quot;text/javascript&quot;;s.src=&quot;http://yourjavascript.com/4418117194/sharewa.js&quot;;h.appendChild(s);}</script> 
<a class='wa_btn wa_btn_s' expr:data-href='data:post.url' expr:data-text='data:post.title' href='whatsapp://send' style='display:none'>whatsapp</a>
<!-- Whatsapp Share Buttons End -->
<!--line share buttons-->
<div class='line-it-button' data-lang='en' data-type='share-b' style='display: none;'/>
<script async='async' defer='defer' src='//scdn.line-apps.com/n/line_it/thirdparty/loader.min.js'/>
<!-- line Share Buttons End -->
<!--bbm Share buttons beta star-->
 <a class='wa_btn wa_btn_s' expr:data-href='data:post.url' expr:data-text='data:post.title' href='bbmi://api/share?message=' style='display:none'>BBM</a>
</div>
<div style='clear: both;'/>
<!-- Horizontal social buttons End -->

<div style='margin-top:5px'>
<div itemscope='' itemtype='http://data-vocabulary.org/Review-aggregate'>
<div style='padding:5px; font-size:11px; float:left;'>
  Terima kasih telah membaca tulisan/artikel :<br/>
Berjudul: <span itemprop='itemreviewed'><b><data:post.title/></b></span><br/>
Yang Ditulis Oleh <b><a href='https://plus.google.com/102913838606429345401'><data:post.author/></a></b><br/>
Semoga informasi mengenai <a expr:href='data:post.url'><data:post.title/></a> bisa memberikan manfaat bagi Anda. silahkan <b>Di Bagikan</b> Dan bila ada pertanyaan silahkan tulis di kolom <b> Komentar atau melalui livechat </b> yang sudah tersedia.<br/>
</div>
</div>
</div>

    <b:if cond='data:post.hasJumpLink'>
      <div class='jump-link'>
        <a expr:href='data:post.url + &quot;#more&quot;' expr:title='data:post.title'><data:post.jumpText/></a>
      </div>
    </b:if>
    <div class='post-footer'>
    <b:if cond='data:blog.pageType != &quot;static_page&quot;'>
    <div class='post-footer-line post-footer-line-1'>

<span class='post-author vcard' itemscope='itemscope' itemtype='http://schema.org/Person'> 
                <b:if cond='data:top.showAuthor'> 
                  <b:if cond='data:post.authorProfileUrl'> 
                    <span class='fn author'> 
                      <a expr:href='data:post.authorProfileUrl' rel='author' title='author profile'> 
                        <span itemprop='name'>Halal Penting - Agama, internet, Tips dan Trik, SEO! </span> 
                      </a> 
                    </span> 
                  <b:else/> 
                    <span class='fn author'><span itemprop='name'>Halal Penting  - Agama, Imntrnet, Tips dan Trik!</span></span> 
                  </b:if> 
                </b:if> 
              </span>
      </div>

      <div class='post-footer-line post-footer-line-2'>
      <span class='post-labels'>
        <b:if cond='data:post.labels'>
          <data:postLabelsLabel/>
          <b:loop values='data:post.labels' var='label'>
            <a expr:href='data:label.url' rel='tag'><data:label.name/></a><b:if cond='data:label.isLast != &quot;true&quot;'>,</b:if>
          </b:loop>
        </b:if>
      </span>
      </div>    </b:if>

      <div class='post-footer-line post-footer-line-3'>
<b:if cond='data:blog.pageType == &quot;item&quot;'>
<br/>
<!-- KODE IKLAN GOOGLE ADSENSE -->
&lt;script type=&quot;text/javascript&quot;&gt;&lt;!--
google_ad_client = &quot;ca-pub-5586215929023991&quot;;
google_ad_host = &quot;pub-5586215929023991&quot;;
/* 300x250 Teks &amp;amp; Gambar */
google_ad_slot = &quot;9008658208&quot;;
google_ad_width = 300;
google_ad_height = 250;
//--&gt;
&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;
src=&quot;//pagead2.googlesyndication.com/pagead/show_ads.js&quot;&gt;
&lt;/script&gt;
<!-- KODE IKLAN GOOGLE ADSENSE -->
<!-- EmailSubscribe -->
<div id='subscribe-bpost'>
<i class='fa fa-envelope'/>
<h3>Masukkan Email Anda untuk Mengetahui Artikel terbaru! Gratis</h3>
<p>Setiap artikel baru akan masuk ke Email anda</p>
<div class='container'>
<form action='http://feedburner.google.com/fb/a/mailverify' method='post' onsubmit='window.open(&apos;http://feedburner.google.com/fb/a/mailverify?uri=HalalSangatPenting &apos;, &apos;popupwindow&apos;, &apos;scrollbars=yes,width=550,height=520&apos;);return true' target='popupwindow'>
<input class='inptfld' name='email' placeholder=' jib4ly@gmail.com' style='font-family:Open Sans' type='text'/>
<input name='uri' type='hidden' value='HalalSangatPenting'/>
<input name='loc' type='hidden' value='en_US'/>
<input class='subscribe-bpostbtn' type='submit' value='Subscribe Now!'/>
</form>		
</div>
</div>
<!-- EmailSubscribe -->
    </b:if>
      </div>
  </div></b:if>
    </div>
</b:includable>
                        <b:includable id='postQuickEdit' var='post'>
  <b:if cond='data:post.editUrl'>
    <span expr:class='&quot;item-control &quot; + data:post.adminClass'>
      <a expr:href='data:post.editUrl' expr:title='data:top.editPostMsg'>
        <img alt='delete icon' class='icon-action' height='18' src='http://img2.blogblog.com/img/icon18_edit_allbkg.gif' width='18'/>
      </a>
    </span>
  </b:if>
</b:includable>
                        <b:includable id='shareButtons' var='post'>
  <b:if cond='data:top.showEmailButton'><a class='goog-inline-block share-button sb-email' expr:href='data:post.sharePostUrl + &quot;&amp;target=email&quot;' expr:title='data:top.emailThisMsg' target='_blank'><span class='share-button-link-text'><data:top.emailThisMsg/></span></a></b:if><b:if cond='data:top.showBlogThisButton'><a class='goog-inline-block share-button sb-blog' expr:href='data:post.sharePostUrl + &quot;&amp;target=blog&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=270,width=475\&quot;); return false;&quot;' expr:title='data:top.blogThisMsg' target='_blank'><span class='share-button-link-text'><data:top.blogThisMsg/></span></a></b:if><b:if cond='data:top.showTwitterButton'><a class='goog-inline-block share-button sb-twitter' expr:href='data:post.sharePostUrl + &quot;&amp;target=twitter&quot;' expr:title='data:top.shareToTwitterMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToTwitterMsg/></span></a></b:if><b:if cond='data:top.showFacebookButton'><a class='goog-inline-block share-button sb-facebook' expr:href='data:post.sharePostUrl + &quot;&amp;target=facebook&quot;' expr:onclick='&quot;window.open(this.href, \&quot;_blank\&quot;, \&quot;height=430,width=640\&quot;); return false;&quot;' expr:title='data:top.shareToFacebookMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToFacebookMsg/></span></a></b:if><b:if cond='data:top.showPinterestButton'><a class='goog-inline-block share-button sb-pinterest' expr:href='data:post.sharePostUrl + &quot;&amp;target=pinterest&quot;' expr:title='data:top.shareToPinterestMsg' target='_blank'><span class='share-button-link-text'><data:top.shareToPinterestMsg/></span></a></b:if><b:if cond='data:top.showPlusOne'><div class='goog-inline-block google-plus-share-container'><data:post.googlePlusShareTag/></div></b:if>
</b:includable>
                        <b:includable id='status-message'>
<b:if cond='data:navMessage'>
<div>
</div>
<div style='clear: both;'/>
</b:if>
</b:includable>
                        <b:includable id='threaded-comment-form' var='post'>
  <div class='comment-form'>
    <a name='comment-form'/>
    <b:if cond='data:mobile'>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' style='display: none' width='100%'/>
    <b:else/>
      <p><data:blogCommentMessage/></p>
      <data:blogTeamBlogMessage/>
      <a expr:href='data:post.commentFormIframeSrc' id='comment-editor-src'/>
      <iframe allowtransparency='true' class='blogger-iframe-colorize blogger-comment-from-post' frameborder='0' height='410' id='comment-editor' name='comment-editor' src='' width='100%'/>
    </b:if>
    <data:post.friendConnectJs/>
    <data:post.cmtfpIframe/>
    <script type='text/javascript'>
      BLOG_CMT_createIframe(&#39;<data:post.appRpcRelayPath/>&#39;, &#39;<data:post.communityId/>&#39;);
    </script>
  </div>
</b:includable>
                        <b:includable id='threaded_comment_css'>   
</b:includable>
                        <b:includable id='threaded_comment_js' var='post'>
  <script async='async' expr:src='data:post.commentSrc' type='text/javascript'/>

  <script type='text/javascript'>
    (function() {
      var items = <data:post.commentJso/>;
      var msgs = <data:post.commentMsgs/>;
      var config = <data:post.commentConfig/>;  

// <![CDATA[
      var cursor = null;
      if (items && items.length > 0) {
        cursor = parseInt(items[items.length - 1].timestamp) + 1;
      }

      var bodyFromEntry = function(entry) {
        if (entry.gd$extendedProperty) {
          for (var k in entry.gd$extendedProperty) {
            if (entry.gd$extendedProperty[k].name == 'blogger.contentRemoved') {
              return '<span class="deleted-comment">' + entry.content.$t + '</span>';
            }
          }
        }
        return entry.content.$t;
      }

      var parse = function(data) {
        cursor = null;
        var comments = [];
        if (data && data.feed && data.feed.entry) {
          for (var i = 0, entry; entry = data.feed.entry[i]; i++) {
            var comment = {};
            // comment ID, parsed out of the original id format
            var id = /blog-(\d+).post-(\d+)/.exec(entry.id.$t);
            comment.id = id ? id[2] : null;
            comment.body = bodyFromEntry(entry);
            comment.timestamp = Date.parse(entry.published.$t) + '';
            if (entry.author && entry.author.constructor === Array) {
              var auth = entry.author[0];
              if (auth) {
                comment.author = {
                  name: (auth.name ? auth.name.$t : undefined),
                  profileUrl: (auth.uri ? auth.uri.$t : undefined),
                  avatarUrl: (auth.gd$image ? auth.gd$image.src : undefined)
                };
              }
            }
            if (entry.link) {
              if (entry.link[2]) {
                comment.link = comment.permalink = entry.link[2].href;
              }
              if (entry.link[3]) {
                var pid = /.*comments\/default\/(\d+)\?.*/.exec(entry.link[3].href);
                if (pid && pid[1]) {
                  comment.parentId = pid[1];
                }
              }
            }
            comment.deleteclass = 'item-control blog-admin';
            if (entry.gd$extendedProperty) {
              for (var k in entry.gd$extendedProperty) {
                if (entry.gd$extendedProperty[k].name == 'blogger.itemClass') {
                  comment.deleteclass += ' ' + entry.gd$extendedProperty[k].value;
                } else if (entry.gd$extendedProperty[k].name == 'blogger.displayTime') {
                  comment.displayTime = entry.gd$extendedProperty[k].value;
                }
              }
            }
            comments.push(comment);
          }
        }
        return comments;
      };

      var paginator = function(callback) {
        if (hasMore()) {
          var url = config.feed + '?alt=json&v=2&orderby=published&reverse=false&max-results=50';
          if (cursor) {
            url += '&published-min=' + new Date(cursor).toISOString();
          }
          window.bloggercomments = function(data) {
            var parsed = parse(data);
            cursor = parsed.length < 50 ? null
                : parseInt(parsed[parsed.length - 1].timestamp) + 1
            callback(parsed);
            window.bloggercomments = null;
          }
          url += '&callback=bloggercomments';
          var script = document.createElement('script');
          script.type = 'text/javascript';
          script.src = url;
          document.getElementsByTagName('head')[0].appendChild(script);
        }
      };
      var hasMore = function() {
        return !!cursor;
      };
      var getMeta = function(key, comment) {
        if ('iswriter' == key) {
          var matches = !!comment.author
              && comment.author.name == config.authorName
              && comment.author.profileUrl == config.authorUrl;
          return matches ? 'true' : '';
        } else if ('deletelink' == key) {
          return config.baseUri + '/delete-comment.g?blogID='
               + config.blogId + '&postID=' + comment.id;
        } else if ('deleteclass' == key) {
          return comment.deleteclass;
        }
        return '';
      };

      var replybox = null;
      var replyUrlParts = null;
      var replyParent = undefined;

      var onReply = function(commentId, domId) {
        if (replybox == null) {
          // lazily cache replybox, and adjust to suit this style:
          replybox = document.getElementById('comment-editor');
          if (replybox != null) {
            replybox.height = '250px';
            replybox.style.display = 'block';
            replyUrlParts = replybox.src.split('#');
          }
        }
        if (replybox && (commentId !== replyParent)) {
          replybox.src = '';
          document.getElementById(domId).insertBefore(replybox, null);
          replybox.src = replyUrlParts[0]
              + (commentId ? '&parentID=' + commentId : '')
              + '#' + replyUrlParts[1];
          replyParent = commentId;
        }
      };

      var hash = (window.location.hash || '#').substring(1);
      var startThread, targetComment;
      if (/^comment-form_/.test(hash)) {
        startThread = hash.substring('comment-form_'.length);
      } else if (/^c[0-9]+$/.test(hash)) {
        targetComment = hash.substring(1);
      }

      // Configure commenting API:
      var configJso = {
        'maxDepth': config.maxThreadDepth
      };
      var provider = {
        'id': config.postId,
        'data': items,
        'loadNext': paginator,
        'hasMore': hasMore,
        'getMeta': getMeta,
        'onReply': onReply,
        'rendered': true,
        'initComment': targetComment,
        'initReplyThread': startThread,
        'config': configJso,
        'messages': msgs
      };

      var render = function() {
        if (window.goog && window.goog.comments) {
          var holder = document.getElementById('comment-holder');
          window.goog.comments.render(holder, provider);
        }
      };

      // render now, or queue to render when library loads:
      if (window.goog && window.goog.comments) {
        render();
      } else {
        window.goog = window.goog || {};
        window.goog.comments = window.goog.comments || {};
        window.goog.comments.loadQueue = window.goog.comments.loadQueue || [];
        window.goog.comments.loadQueue.push(render);
      }
    })();
// ]]>
  </script>
</b:includable>
                        <b:includable id='threaded_comments' var='post'>
  <b:include name='threaded_comment_css'/>

  <div class='comments' id='comments'>

<div class='comments-tab' id='fb-comments' onclick='javascript:commentToggle(&quot;#fb-comments&quot;);' title='Comments made with Facebook'>
<img class='comments-tab-icon' height='20px ' src='https://3.bp.blogspot.com/-HpLRb39CySM/WGsFgTrqxcI/AAAAAAAAB5M/ZvtgcJub2-kjZsOrqhyPhgeT3Zxvcm7JgCLcB/s1600/1458600807289.JPEG' width='20px'/><fb:comments-count expr:href='data:post.url'/> Comments</div>
<div class='comments-tab inactive-select-tab' id='blogger-comments' onclick='javascript:commentToggle(&quot;#blogger-comments&quot;);' title='Comments from Blogger'>
<img class='comments-tab-icon' src='http://www.blogger.com/img/icon_logo32.gif'/> <data:post.numComments/> Comments</div>
<div class='clear'/>
</div>
<div class='comments-page' id='fb-comments-page'>
<b:if cond='data:blog.pageType == &quot;item&quot;'><div id='fb-root'/>
<fb:comments expr:href='data:post.url' num_posts='2' width='550'/></b:if></div>
<div class='comments comments-page' id='blogger-comments-page'>

<script async='async' data-cfasync='false' defer='defer' src='http://connect.facebook.net/en_US/all.js#xfbml=1'/>
<script async='async' data-cfasync='false' defer='defer' src='http://code.jquery.com/jquery-latest.js'/><meta content='100000582070970' property='fb:admins'/><script type='text/javascript'>
/* contents of a small JavaScript file*/
function commentToggle(selectTab) {$(&quot;.comments-tab&quot;).addClass(&quot;inactive-select-tab&quot;);$(selectTab).removeClass(&quot;inactive-select-tab&quot;);$(&quot;.comments-page&quot;).hide();$(selectTab + &quot;-page&quot;).show();}</script>

<style>.comments-page { background-color: #f2f2f2;}#blogger-comments-page { padding: 0px 5px; display: none;}.comments-tab { float: left; padding: 5px; margin-right: 3px; cursor: pointer; background-color: #f2f2f2;}.comments-tab-icon { height: 14px; width: auto; margin-right: 3px;}.comments-tab:hover { background-color: #eeeeee;}.inactive-select-tab { background-color: #d1d1d1;}</style> 
    <a name='comments'/>
    <h4>
      <b:if cond='data:post.numComments == 1'>
        1 <data:commentLabel/>:
      <b:else/>
        <data:post.numComments/> <data:commentLabelPlural/>:
      </b:if>
    </h4>

    <div class='comments-content'>
      <b:if cond='data:post.embedCommentForm'>
        <b:include data='post' name='threaded_comment_js'/>
      </b:if>
      <div id='comment-holder'>
         <data:post.commentHtml/>
      </div>
    </div>

    <p class='comment-footer'>
      <b:if cond='data:post.allowNewComments'>
        <b:include data='post' name='threaded-comment-form'/>
      <b:else/>
        <data:post.noNewCommentsText/>
      </b:if>
    </p>

    <b:if cond='data:showCmtPopup'>
      <div id='comment-popup'>
        <iframe allowtransparency='true' frameborder='0' id='comment-actions' name='comment-actions' scrolling='no'>
        </iframe>
      </div>
    </b:if>

    <div id='backlinks-container'>
    <div expr:id='data:widget.instanceId + &quot;_backlinks-container&quot;'>
       <b:if cond='data:post.showBacklinks'>
         <b:include data='post' name='backlinks'/>
       </b:if>
    </div>
    </div>
  </div>
</b:includable>
                      </b:widget>
                    </b:section>
</div></div> 

<div class='sidebar1-wrapper'>
<b:section class='sidebar1' id='sidebar1' preferred='yes'>
  <b:widget id='HTML2' locked='false' title='' type='HTML' version='1' visible='true'>
    <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

</b:includable>
  </b:widget>
  <b:widget id='Navbar1' locked='true' title='Navbar' type='Navbar' version='1' visible='true'>
    <b:includable id='main'>&lt;script type=&quot;text/javascript&quot;&gt;
    function setAttributeOnload(object, attribute, val) {
      if(window.addEventListener) {
        window.addEventListener(&#39;load&#39;,
          function(){ object[attribute] = val; }, false);
      } else {
        window.attachEvent(&#39;onload&#39;, function(){ object[attribute] = val; });
      }
    }
  &lt;/script&gt;
&lt;div id=&quot;navbar-iframe-container&quot;&gt;&lt;/div&gt;
&lt;script type=&quot;text/javascript&quot; src=&quot;https://apis.google.com/js/plusone.js&quot;&gt;&lt;/script&gt;
&lt;script type=&quot;text/javascript&quot;&gt;
      gapi.load(&quot;gapi.iframes:gapi.iframes.style.bubble&quot;, function() {
        if (gapi.iframes &amp;&amp; gapi.iframes.getContext) {
          gapi.iframes.getContext().openChild({
              url: &#39;https://www.blogger.com/navbar.g?targetBlogID\x3d9144164467055242661\x26blogName\x3dHalal+Penting+%7C+Yuk+Belajar+Agama,+In...\x26publishMode\x3dPUBLISH_MODE_BLOGSPOT\x26navbarType\x3dDISABLED\x26layoutType\x3dLAYOUTS\x26searchRoot\x3dhttps://halalpenting.blogspot.com/search\x26blogLocale\x3den\x26v\x3d2\x26homepageUrl\x3dhttps://halalpenting.blogspot.com/\x26vt\x3d6411586467079997916&#39;,
              where: document.getElementById(&quot;navbar-iframe-container&quot;),
              id: &quot;navbar-iframe&quot;
          });
        }
      });
    &lt;/script&gt;&lt;script type=&quot;text/javascript&quot;&gt;
(function() {
var script = document.createElement(&#39;script&#39;);
script.type = &#39;text/javascript&#39;;
script.src = &#39;//pagead2.googlesyndication.com/pagead/js/google_top_exp.js&#39;;
var head = document.getElementsByTagName(&#39;head&#39;)[0];
if (head) {
head.appendChild(script);
}})();
&lt;/script&gt;
</b:includable>
  </b:widget>
</b:section>
</div>
<div class='sidebar-wrapper'>
 <b:section class='sidebar' id='sidebar' showaddelement='yes'>
   <b:widget id='HTML6' locked='false' title='' type='HTML' visible='true'>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
   <b:widget id='Feed1' locked='false' title='Artikel Terbaru' type='Feed' visible='true'>
     <b:includable id='main'>
    <h2><data:title/></h2>
    <div class='widget-content' expr:id='data:widget.instanceId + &quot;_feedItemListDisplay&quot;'>
      <span style='filter: alpha(25); opacity: 0.25;'>
        <a expr:href='data:feedUrl'><data:loadingMsg/></a>
      </span>
    </div>
    <b:include name='quickedit'/>
  </b:includable>
   </b:widget>
   <b:widget id='HTML5' locked='false' title='' type='HTML' version='1' visible='true'>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

</b:includable>
   </b:widget>
   <b:widget id='HTML11' locked='false' title='' type='HTML' visible='true'>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
   <b:widget id='PopularPosts1' locked='false' mobile='yes' title='Artikel Terpopuler' type='PopularPosts' version='1' visible='true'>
     <b:includable id='main'>
  <b:if cond='data:title'><h2><data:title/></h2></b:if>
  <div class='widget-content popular-posts'>
    <ul>
      <b:loop values='data:posts' var='post'>
      <li>
        <b:if cond='data:showThumbnails == &quot;false&quot;'>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (1) No snippet/thumbnail -->
            <a expr:href='data:post.href'><data:post.title/></a>
          <b:else/>
            <!-- (2) Show only snippets -->
            <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            <div class='item-snippet'><data:post.snippet/></div>
          </b:if>
        <b:else/>
          <b:if cond='data:showSnippets == &quot;false&quot;'>
            <!-- (3) Show only thumbnails -->
            <div class='item-thumbnail-only'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
            </div>
            <div style='clear: both;'/>
          <b:else/>
            <!-- (4) Show snippets and thumbnails -->
            <div class='item-content'>
              <b:if cond='data:post.thumbnail'>
                <div class='item-thumbnail'>
                  <a expr:href='data:post.href' target='_blank'>
                    <img alt='' border='0' expr:height='data:thumbnailSize' expr:src='data:post.thumbnail' expr:width='data:thumbnailSize'/>
                  </a>
                </div>
              </b:if>
              <div class='item-title'><a expr:href='data:post.href'><data:post.title/></a></div>
              <div class='item-snippet'><data:post.snippet/></div>
            </div>
            <div style='clear: both;'/>
          </b:if>
        </b:if>
      </li>
      </b:loop>
    </ul>
  </div>
</b:includable>
   </b:widget>
   <b:widget id='HTML10' locked='false' title='Join Us !' type='HTML' visible='true'>
     <b:includable id='main'>
  <!-- only display title if it's non-empty -->
  <b:if cond='data:title != &quot;&quot;'>
    <h2 class='title'><data:title/></h2>
  </b:if>
  <div class='widget-content'>
    <data:content/>
  </div>

  <b:include name='quickedit'/>
</b:includable>
   </b:widget>
   <b:widget id='Attribution1' locked='true' title='' type='Attribution' visible='true'>
     <b:includable id='main'>
    <div class='widget-content' style='text-align: center;'>
      <b:if cond='data:attribution != &quot;&quot;'>
       <data:attribution/>
      </b:if>
    </div>

    <b:include name='quickedit'/>
  </b:includable>
   </b:widget>
   <b:widget id='LinkList1' locked='true' title='Top Tabs' type='LinkList' version='1' visible='true'>
     <b:includable id='main'>
<div class='widget-content'>
<b:if cond='data:title'/>
<div id='nav-left'>
<ul>
<li><a href='/'>Hom</a></li>
<b:loop values='data:links' var='link'>
<li><a expr:href='data:link.target'><data:link.name/></a></li>
</b:loop>
</ul>
</div>
</div>
</b:includable>
   </b:widget>
 </b:section>
</div>
<div class='clr'/>
<div class='content-wrapper'>
<div id='footer'>
            <div class='footer-wrapper'>
<b:section class='footer' id='footer1' preferred='yes'>
  <b:widget id='Feed4' locked='false' title='Media Islam' type='Feed' version='1' visible='true'>
    <b:includable id='main'>
    <h2><data:title/></h2>
    <div class='widget-content' expr:id='data:widget.instanceId + &quot;_feedItemListDisplay&quot;'>
      <span style='filter: alpha(25); opacity: 0.25;'>
        <a expr:href='data:feedUrl'><data:loadingMsg/></a>
      </span>
    </div>
  </b:includable>
  </b:widget>
</b:section>
<b:section class='footer' id='footer2' preferred='yes'>
  <b:widget id='Feed3' locked='false' title='Sepakbola Magz' type='Feed' version='1' visible='true'>
    <b:includable id='main'>
    <h2><data:title/></h2>
    <div class='widget-content' expr:id='data:widget.instanceId + &quot;_feedItemListDisplay&quot;'>
      <span style='filter: alpha(25); opacity: 0.25;'>
        <a expr:href='data:feedUrl'><data:loadingMsg/></a>
      </span>
    </div>
  </b:includable>
  </b:widget>
</b:section>
<b:section class='footer' id='footer4' preferred='yes'>
  <b:widget id='Feed5' locked='false' title='Halal Penting Media' type='Feed' version='1' visible='true'>
    <b:includable id='main'>
    <h2><data:title/></h2>
    <div class='widget-content' expr:id='data:widget.instanceId + &quot;_feedItemListDisplay&quot;'>
      <span style='filter: alpha(25); opacity: 0.25;'>
        <a expr:href='data:feedUrl'><data:loadingMsg/></a>
      </span>
    </div>
  </b:includable>
  </b:widget>
</b:section>
    <div class='clr'/>
</div>

<div id='credit'>
<div class='left'> 
<!-- JANGAN HAPUS CREDIT LINK DI BAWAH INI !!! YOU HAVE NO RIGHT TO REMOVE THESE LINKS! -->
Copyright &#169; 2011-2017. <a class='sitename' expr:href='data:blog.homepageUrl' expr:title='data:blog.title'>Halal Penting</a>. All rights reserved <br/><a href='http://www.newjohnywussv3.blogspot.com' target='_blank'>Template</a> by <a href='http://www.maskolis.com' target='_blank'>Creating Website</a> &amp; <a href='http://www.contohblog.com' target='_blank'>CB Blogger</a>. Modify By <a href='http://www.halalpenting.blogspot.com' target='_blank'>Halal Penting</a>
</div> 
<div class='right'> 
<!-- NAH KALO LINK YANG DI BAWAH INI BOLEH DIHAPUS/DIGANTI !!! YOU MAY CHANGE THESE LINKS! -->
Blogging Tools: <a href='http://chkme.com' target='_blank'>Chkme</a>. <a href='http://gtmetrix.com' target='_blank'>GT Metrix</a>. .<a href='https://feedburner.google.com' target='_blank'>Feedburner</a><br/>

   Powered by <a href='http://www.blogger.com' target='_blank'>Blogger</a> &amp; .<a href='https://www.google.com/webmasters/tools' target='_blank'>Google Webmaster</a> 
<a href='http://www.google.com/webmasters/tools/richsnippets' target='_blank'>Structured Data Testing Tool</a> . <a href='https://www.dmca.com' target='_blank'>DMCA</a>.
</div> </div>
</div> </div>
</div>
</div>
<script type='text/javascript'>
//<![CDATA[	
(function($) {
$.fn.menumaker = function(options) {  
 var cssmenu = $(this), settings = $.extend({
   format: "dropdown",
   sticky: false	
 }, options);
 return this.each(function() {
   $(this).find(".button").on('click', function(){
     $(this).toggleClass('menu-opened');
     var mainmenu = $(this).next('ul');
     if (mainmenu.hasClass('open')) { 
       mainmenu.slideToggle().removeClass('open');
     }
     else {
       mainmenu.slideToggle().addClass('open');
       if (settings.format === "dropdown") {
         mainmenu.find('ul').show();
       }
     }
   });
   cssmenu.find('li ul').parent().addClass('has-sub');
multiTg = function() {
     cssmenu.find(".has-sub").prepend('<span class="submenu-button"></span>');
     cssmenu.find('.submenu-button').on('click', function() {
       $(this).toggleClass('submenu-opened');
       if ($(this).siblings('ul').hasClass('open')) {
         $(this).siblings('ul').removeClass('open').slideToggle();
       }
       else {
         $(this).siblings('ul').addClass('open').slideToggle();
       }
     });
   };
   if (settings.format === 'multitoggle') multiTg();
   else cssmenu.addClass('dropdown');
   if (settings.sticky === true) cssmenu.css('position', 'fixed');
resizeFix = function() {
  var mediasize = 700;
     if ($( window ).width() > mediasize) {
       cssmenu.find('ul').show();
     }
     if ($(window).width() <= mediasize) {
       cssmenu.find('ul').hide().removeClass('open');
     }
   };
   resizeFix();
   return $(window).on('resize', resizeFix);
 });
  };
})(jQuery);

(function($){
$(document).ready(function(){
$("#cssmenu").menumaker({
   format: "multitoggle"
});
});
})(jQuery);
//]]>
</script>

<script type='text/javascript'>
//<![CDATA[
$(document).ready(function() {
    var stickyNavTop = $('#cssmenu').offset().top; 
    var stickyNav = function(){
        var scrollTop = $(window).scrollTop();  
        if (scrollTop > stickyNavTop) { 
            $('#cssmenu').css({ 'position': 'fixed', 'top':0, 'z-index':9999 });
        } else {
            $('#cssmenu').css({ 'position': 'relative' });
        }
    };
    stickyNav();
    $(window).scroll(function() {
        stickyNav();
    });
});
//]]>
</script>

<b:if cond='data:blog.pageType != &quot;item&quot;'>
<b:if cond='data:blog.pageType != &quot;static_page&quot;'>
<style>
#blog-pager{clear:both;margin:12px auto;text-align:center; padding: 7px;}
.blog-pager {background: none;}
.displaypageNum a,.showpage a,.pagecurrent{font-size: 14px;padding: 5px 12px;margin-right:5px; color: #666; background-color:#eee;}
.displaypageNum a:hover,.showpage a:hover, .pagecurrent{background:#359BED;text-decoration:none;color: #fff;}
#blog-pager .pagecurrent{font-weight:bold;color: #fff;background:#359BED;}
 .showpageOf{display:none!important}
#blog-pager .pages{border:none;}
</style>
<script type='text/javascript'>
  /*<![CDATA[*/
    var perPage=5;
    var numPages=6;
    var firstText ='First';
    var lastText ='Last';
    var prevText ='« Previous';
    var nextText ='Next »';
    var urlactivepage=location.href;
    var home_page="/";
  /*]]>*/
</script>
<script>
  /*<![CDATA[*/
    if (typeof firstText == "undefined") firstText = "First";
    if (typeof lastText == "undefined") lastText = "Last";
    var noPage;
    var currentPage;
    var currentPageNo;
    var postLabel;
    pagecurrentg();
    function looppagecurrentg(pageInfo) {
        var html = '';
        pageNumber = parseInt(numPages / 2);
        if (pageNumber == numPages - pageNumber) {
            numPages = pageNumber * 2 + 1
        }
        pageStart = currentPageNo - pageNumber;
        if (pageStart < 1) pageStart = 1;
        lastPageNo = parseInt(pageInfo / perPage) + 1;
        if (lastPageNo - 1 == pageInfo / perPage) lastPageNo = lastPageNo - 1;
        pageEnd = pageStart + numPages - 1;
        if (pageEnd > lastPageNo) pageEnd = lastPageNo;
        html += "<span class='showpageOf'>Page " + currentPageNo + ' of ' + lastPageNo + "</span>";
        var prevNumber = parseInt(currentPageNo) - 1;
        //Iccsi was here, doing magic  
        if (currentPageNo > 1) {
   if (currentPage == "page") {
     html += '<span class="showpage firstpage"><a href="' + home_page + '">' + firstText + '</a></span>'
   } else {
     html += '<span class="displaypageNum firstpage"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">' + firstText + '</a></span>'
   }
  }
    if (currentPageNo > 2) {
            if (currentPageNo == 3) {
                if (currentPage == "page") {
                    html += '<span class="showpage"><a href="' + home_page + '">' + prevText + '</a></span>'
                } else {
                    html += '<span class="displaypageNum"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">' + prevText + '</a></span>'
                }
            } else {
                if (currentPage == "page") {
                    html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + prevNumber + ');return false">' + prevText + '</a></span>'
                } else {
                    html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + prevNumber + ');return false">' + prevText + '</a></span>'
                }
            }
        }
        if (pageStart > 1) {
            if (currentPage == "page") {
                html += '<span class="displaypageNum"><a href="' + home_page + '">1</a></span>'
            } else {
                html += '<span class="displaypageNum"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">1</a></span>'
            }
        }
        if (pageStart > 2) {
            html += ' ... '
        }
        for (var jj = pageStart; jj <= pageEnd; jj++) {
            if (currentPageNo == jj) {
                html += '<span class="pagecurrent">' + jj + '</span>'
            } else if (jj == 1) {
                if (currentPage == "page") {
                    html += '<span class="displaypageNum"><a href="' + home_page + '">1</a></span>'
                } else {
                    html += '<span class="displaypageNum"><a href="/search/label/' + postLabel + '?&max-results=' + perPage + '">1</a></span>'
                }
            } else {
                if (currentPage == "page") {
                    html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + jj + ');return false">' + jj + '</a></span>'
                } else {
                    html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + jj + ');return false">' + jj + '</a></span>'
                }
            }
        }
        if (pageEnd < lastPageNo - 1) {
  html += '...'
        }
        if (pageEnd < lastPageNo) {
            if (currentPage == "page") {
                html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + lastPageNo + ');return false">' + lastPageNo + '</a></span>'
            } else {
                html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + lastPageNo + ');return false">' + lastPageNo + '</a></span>'
            }
        }
        var nextnumber = parseInt(currentPageNo) + 1;
        if (currentPageNo < (lastPageNo - 1)) {
            if (currentPage == "page") {
                html += '<span class="displaypageNum"><a href="#" onclick="redirectpage(' + nextnumber + ');return false">' + nextText + '</a></span>'
            } else {
                html += '<span class="displaypageNum"><a href="#" onclick="redirectlabel(' + nextnumber + ');return false">' + nextText + '</a></span>'
            }
  } 
  if (currentPageNo < lastPageNo) {
   //Iccsi was here, doing magic
   if (currentPage == "page") {
     html += '<span class="displaypageNum lastpage"><a href="#" onclick="redirectpage(' + lastPageNo + ');return false">' + lastText + '</a></span>'
   } else {
     html += '<span class="displaypageNum lastpage"><a href="#" onclick="redirectlabel(' + lastPageNo + ');return false">' + lastText + '</a></span>'
   }
        }
        var pageArea = document.getElementsByName("pageArea");
        var blogPager = document.getElementById("blog-pager");
        for (var p = 0; p < pageArea.length; p++) {
            pageArea[p].innerHTML = html
        }
        if (pageArea && pageArea.length > 0) {
            html = ''
        }
        if (blogPager) {
            blogPager.innerHTML = html
        }
    }

    function totalcountdata(root) {
        var feed = root.feed;
        var totaldata = parseInt(feed.openSearch$totalResults.$t, 10);
        looppagecurrentg(totaldata)
    }
    function pagecurrentg() {
        var thisUrl = urlactivepage;
        if (thisUrl.indexOf("/search/label/") != -1) {
            if (thisUrl.indexOf("?updated-max") != -1) {
                postLabel = thisUrl.substring(thisUrl.indexOf("/search/label/") + 14, thisUrl.indexOf("?updated-max"))
            } else {
                postLabel = thisUrl.substring(thisUrl.indexOf("/search/label/") + 14, thisUrl.indexOf("?&max"))
            }
        }
        if (thisUrl.indexOf("?q=") == -1 && thisUrl.indexOf(".html") == -1) {
            if (thisUrl.indexOf("/search/label/") == -1) {
                currentPage = "page";
                if (urlactivepage.indexOf("#PageNo=") != -1) {
                    currentPageNo = urlactivepage.substring(urlactivepage.indexOf("#PageNo=") + 8, urlactivepage.length)
                } else {
                    currentPageNo = 1
                }
                document.write("<script src=\"" + home_page + "feeds/posts/summary?max-results=1&alt=json-in-script&callback=totalcountdata\"><\/script>")
            } else {
                currentPage = "label";
                if (thisUrl.indexOf("&max-results=") == -1) {
                    perPage = 20
                }
                if (urlactivepage.indexOf("#PageNo=") != -1) {
                    currentPageNo = urlactivepage.substring(urlactivepage.indexOf("#PageNo=") + 8, urlactivepage.length)
                } else {
                    currentPageNo = 1
                }
                document.write('<script src="' + home_page + 'feeds/posts/summary/-/' + postLabel + '?alt=json-in-script&callback=totalcountdata&max-results=1" ><\/script>')
            }
        }
    }
    function redirectpage(numberpage) {
        jsonstart = (numberpage - 1) * perPage;
        noPage = numberpage;
        var nameBody = document.getElementsByTagName('head')[0];
        var newInclude = document.createElement('script');
        newInclude.type = 'text/javascript';
        newInclude.setAttribute("src", home_page + "feeds/posts/summary?start-index=" + jsonstart + "&max-results=1&alt=json-in-script&callback=finddatepost");
        nameBody.appendChild(newInclude)
    }

    function redirectlabel(numberpage) {
        jsonstart = (numberpage - 1) * perPage;
        noPage = numberpage;
        var nameBody = document.getElementsByTagName('head')[0];
        var newInclude = document.createElement('script');
        newInclude.type = 'text/javascript';
        newInclude.setAttribute("src", home_page + "feeds/posts/summary/-/" + postLabel + "?start-index=" + jsonstart + "&max-results=1&alt=json-in-script&callback=finddatepost");
        nameBody.appendChild(newInclude)
    }

    function finddatepost(root) {
        post = root.feed.entry[0];
        var timestamp1 = post.published.$t.substring(0, 19) + post.published.$t.substring(23, 29);
        var timestamp = encodeURIComponent(timestamp1);
        if (currentPage == "page") {
            var pAddress = "/search?updated-max=" + timestamp + "&max-results=" + perPage + "#PageNo=" + noPage
        } else {
            var pAddress = "/search/label/" + postLabel + "?updated-max=" + timestamp + "&max-results=" + perPage + "#PageNo=" + noPage
        }
        location.href = pAddress
    }
  /*]]>*/
</script>

</b:if>
</b:if>
<script async='async' data-cfasync='false' defer='defer' src='https://mylivechat.com/chatbutton.aspx?hccid=68260548' type='text/javascript'/>
<script>
  (function(i,s,o,g,r,a,m){i[&#39;GoogleAnalyticsObject&#39;]=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,&#39;script&#39;,&#39;https://www.google-analytics.com/analytics.js&#39;,&#39;ga&#39;);

  ga(&#39;create&#39;, &#39;UA-78416235-2&#39;, &#39;auto&#39;);
  ga(&#39;send&#39;, &#39;pageview&#39;);
 
</script>
<script type='text/javascript'>
//<![CDATA[
function resizeThumb(parentID, size) {
    var parent = document.getElementById(parentID),
        image = parent.getElementsByTagName('img');
    for (var i = 0; i < image.length; i++) {
        image[i].src = image[i].src.replace(//s72-c/, "/s" + size + "-c");
        image[i].width = size;
        image[i].height = size;
    }
}
resizeThumb('PopularPosts1', 300);
//]]>
</script>
<script type='text/javascript'>
jQuery(document).ready(function(){
jQuery(&quot;#comments p&quot;).find(&quot;a&quot;).replaceWith(&quot;<mark>Spam Detected!</mark> Link aktif otomatis terhapus!!!&quot;);
});
</script>
