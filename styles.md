# bemcustom-style

## Paddings/Margins
  * **xxs** - 4px
  * **xs** - 8px
  * **s** - 16px
  * **m** - 24px
  * **l** - 32px
  * **xl** - 48px
  * **xxl** - 96px


## Avatars
  * **s** - 60px
  * **m** - 90px
  * **l** - 120px
  
## Icons
 * **s** - 24px
 * **m** - 48px
 * **l** - 96px 


# bemcustom-colors
## the Big Colors theory - http://codepen.io/koloskof/pen/NGmeGL

## project
 * #fc0  - hsl(48, 100%, 50%) / $project 
 * #ffdb4d - hsl(48, 100%, 65%) / lighten($project, 65%)
 * #ffeba0 - hsl(47, 100%, 81%) / lighten($project, 81%)

## base
 * #000 - hsl(0, 0%, 0%)
 * #2e2e2e - hsl(0, 0%, 18%) / alpha($base, 18%)
 * #999 - hsl(0, 0%, 60%)  / lighten($base, 60%)
 * #ccc - hsl(0, 0%, 80%)  / lighten($base, 80%)
 
## normal
 * #f6f5f3 -  hsl(40, 14%, 96%) / $normal 
 * #e0ddd6 -  hsl(40, 14%, 86%) / lighten($normal, 86%)
 
## clean
  * #fff - hsl(0, 0%, 100%) / $clean
  
## link
  * #44b  - hsl(240, 47%, 50%) / $link
  
## alert
  * #e00  - hsl(0, 100%, 47%) / $alert
  
## active
  * #070  - hsl(120, 100%, 23%) / $active


#bemcustom-typography

```
.text
  &_size
    &_xs
      font-size: 13px
    &_s
      font-size: 15px /* bem-components s-size */
    &_m
      font-size: 18px /* bem-components l-size */
    &_l
      font-size: 24px
    &_xl
      font-size: 32px

  &_view
    &_base
      color: #000
    &_clear
      color: #fff
    &_project
      color: #ffdb4d
    &_link
      color: #44b
    &_alert
      color: #e61400
    &_active
      color: #060

  &_weight
    &_bold
      font-weight: bold

  &_transform
    transform: uppercase

  &_display
    &_block
      display: block
    &_inline-block
      display: inline-block
    &_inline
      display: inline
 ```
