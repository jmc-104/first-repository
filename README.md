# first-repository
created nov .25,2020

In my attempt to speed up my site's load speed, here
are my versions of react.lazy as the code is originally
provided, and as my version of 'json'.

My Json version:

import React, { lazy } from 'react.lazy.js';

<const AvatarComponent>;

"script type = "json.js";
<script>
"Site" = "https://www.natureseccentricity.com?url={pagetitle}";
"@name" = "#Videoplayer1.settings.list";
 "@list" = "pause, stop, rewind, fast forward, volume up, volume down";
 </script>;
 </const AvatarComponent>;

My version of the original code:

import React, { lazy } from 'react';
const #videoplayer1.settings = lazy(url ("settings list url") => import
('settings.list/#videoplayer1')/url);

