<template>
    <div id="editor">
        <nav>
            <ol>
                <li class="active"> 
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-shenfenzheng"></use>
                    </svg>
                    <span>基本信息</span>
                </li>
                <li>
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-work0"></use>
                    </svg>
                    <span>工作经历</span>
                </li>
                <li>
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-yonggong"></use>
                    </svg>
                    <span>项目经历</span>
                </li>
                <li>
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-icskill"></use>
                    </svg>
                    <span>技能掌握</span>
                </li>
                <li>
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-xueli"></use>
                    </svg>
                    <span>个人荣誉</span>
                </li>
                 <li>
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-aixin"></use>
                    </svg>
                    <span>兴趣爱好</span>
                </li>      
                <li>
                    <svg class="icon" aria-hidden="true">
                        <use xlink:href="#icon-dianhua"></use>
                    </svg>
                    <span>联系方式</span>
                </li>
            </ol>
        </nav>
        <ol class="edit_box">dscvf</ol>
    </div>
</template>

<style lang="scss">
#editor {
  border: 1px solid red;
  display: flex;
  > nav{
      background-color: #F4F4F4;
      width:160px;
      > ol > li{
          display:flex;
          align-items: center;
          > span {
              color:#A5ADB0;
          }
          &.active {
              background: rgb(221, 239, 255);
              > .icon{
                  fill:#2B465D
              }
              > span{
                  color:#2B465D
              }
          }
      }
  }
  > ol{
      background:#2B465D;
      flex-grow: 1;
  }
}
</style>
