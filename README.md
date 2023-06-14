**What is this ?**
Get shadows by installing this package.

**Installation**
npm i npm-shadowed
Then...

import { shadow } from 'shadow';

shadow({
    shadow_type: 'soft',
    padding: false
});

**Options**
Shadow supports 2 options, both of which are optional:
  1) shadow_type - hard | soft (Defaults to soft)
  2) padding - boolean (Defaults to false)
