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

## Сolors
## the Big Colors theory - http://codepen.io/koloskof/pen/NGmeGL

### project
 * $project - hsl(48, 100%, 50%) - #fc0 
 * lighten($project, 65%) - hsl(48, 100%, 65%) - #ffdb4d
 * lighten($project, 81%) - hsl(47, 100%, 81%) - #ffeba0   

### base
 * **$base** - hsl(0, 0%, 0%) - #000
 * **lighten($base, 18%)** - hsl(0, 0%, 18%) - #2e2e2e 
 * **lighten($base, 60%)** - hsl(0, 0%, 60%) -  #999
 * **lighten($base, 80%)** - hsl(0, 0%, 80%) - #ccc
 
### normal
 * **$normal** - hsl(40, 14%, 96%) - #f6f5f3
 * **lighten($normal, 86%)** - hsl(40, 14%, 86%) - #e0ddd6   
 
### clean
 * **$clean** - hsl(0, 0%, 100%) - #fff
  
### link
 * **$link** - hsl(240, 47%, 50%) - #44b 
  
### alert
 * **$alert** - hsl(0, 100%, 47%) - #e00
  
### active
 * **$active** - hsl(120, 100%, 23%) - #070  


## Typography

### text
  ### _size
    **_xs**
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
