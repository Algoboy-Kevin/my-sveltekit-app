<div class="h-screen drawer drawer-mobile w-full">
    <input id="my-drawer-2" type="checkbox" class="drawer-toggle">
    <div class="drawer-content flex flex-col items-center justify-center">
        <!--  Page content here -->
        <slot></slot>
    </div> 
    <div class="drawer-side">
      <label for="my-drawer-2" class="drawer-overlay"></label> 
      <ul class="menu p-4 overflow-y-auto w-80 bg-base-100 text-base-content">
        <!-- Sidebar content here -->
        <li><a>Sidebar Item 1</a></li>
        <li><a>Sidebar Item 2</a></li>
      </ul>
    
    </div>
</div>