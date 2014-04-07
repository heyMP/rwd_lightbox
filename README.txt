Responsive Lightbox
===================

This module adds a 'Responsive Image' field formatter for images. This field formatter allows you to choose an image style for the 'thubmnail' and 'large' image versions.  It will wrap the 'thumbnail' image with a link to the 'large' image. 

Usage:

Formatter Output
<a class="rwd-lightbox" href="path-to-large-image"><img src="path-to-thubmnail-image"></a>

jQuery selector
$('rwd-lightbox').imagelightbox({
    allowedTypes: 'all'
});
