---
layout: page
title: About
comments: true
permalink: /about/
---

<!-- Chinese Version -->
<div class="zh post-container">
    <p>中度留杭需求者。</p>
</div>

<script src="https://cdnjs.loli.net/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<script src="//cdn1.lncld.net/static/js/3.0.4/av-min.js"></script>
<script src="//unpkg.com/valine/dist/Valine.min.js"></script>

<p><br/><br/><br/><br/><br/><br>
<hr/><br/>评论一下：</p>
<div id="valine_comment" class="fb_comments_container"></div>
<script>
    var notify = '{{site.valine.notify}}' === true;
    var verify = '{{site.valine.verify}}.>' === true;
    var visitor = '{{site.valine.visitor}}.>' === true;

    new Valine({
        av: AV,
        el: '#valine_comment',
        notify: notify,
        verify: verify,
        // smiles_url: '/smiles',
        visitor: visitor,
        app_id: '{{site.valine.app_id}}',
        app_key: '{{site.valine.app_key}}',
        placeholder: '{{site.valine.placeholder}}',
        avatar: '{{site.valine.avatar}}'
    });
</script>