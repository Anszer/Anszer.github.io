---
title:  甜品台——简·爱
tags:
  - 甜品台
  - 情侣
  - 婚礼
images:
  - https://images.unsplash.com/photo-1592189169683-8119db845f77?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=334&q=80
  - https://images.unsplash.com/photo-1560421741-3c02314dce9b?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=crop&w=1050&q=80
  - https://hbimg.huabanimg.com/27f344c0c9ac005b979702215a697307c9b8f89dbbff-MLhhXx_fw658/format/webp
  - https://hbimg.huabanimg.com/184090ddfa3709124a0a00629e1250e819293ad1a80fc-KO4698_fw658/format/webp
  - https://hbimg.huabanimg.com/dd3b6c37e1c78e228dbd18d2b8857c11589b2f23c4042-pVET9v_fw658/format/webp
  - https://hbimg.huabanimg.com/84cd4ae30f5e5ce6ab193f83c84ca738573ec9ab6643c-HutzYz_fw658/format/webp
---

最经典的配色，最隽永的爱情。

<!--more-->

我爱你，无关身份。[GitHub repo](https://github.com/sfreytag/friday-theme/tree/master/_posts).

平等、自由、互相尊重。

<div class="card-columns">
    {% for img in page.images %}
    <div class="card" data-toggle="modal" data-target="#exampleModal" data-img="{{ img }}">
        <img class="card-img-top" src="{{ img }}" />
    </div>
    {% endfor %}
</div>

(The photos are from [Unsplash](http://www.unsplash.com)!)

<div class="modal fade" id="exampleModal">
  <div class="modal-dialog modal-lg modal-dialog-centered">
    <div class="modal-content">
      <div class="modal-body">
        <img class="modal-img w-100" />
      </div>
    </div>
  </div>
</div>

<script type="text/javascript">
  $(document).ready(function() {
    $('#exampleModal').on('show.bs.modal', function (event) {
      var button = $(event.relatedTarget)
      var img = button.data('img')
      var modal = $(this)
      modal.find('.modal-img').attr('src', img)
    })
  })
</script>



