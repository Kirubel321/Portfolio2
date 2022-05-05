# Portfolio2

# Portfolio

## Bootstrap Navbar

These responsive navbar will be collapsed on devices having small viewports like mobile phones but expand when user click the toggle button. However, it will be horizontal as normal on the medium and large devices such as laptop or desktop.

## Bootstrap Containers

Containers are the most basic layout element in Bootstrap and are required when using the grid system. Containers are basically used to wrap content with some padding. They are also used to align the content horizontally center on the page in case of fixed width layout. Bootstrap provides three different types containers: .container, which has a max-width at each responsive breakpoint. .container-fluid, which has 100% width at all breakpoints. .container-{breakpoint}, which has 100% width until the specified breakpoint. The table below illustrates how each container's max-width changes across each breakpoint. For example, when using the .container class the actual width of the container will be 100% if the viewport width is <576px, 540px if the viewport width is ≥576px but <768px, 720px if the viewport width is ≥768px but <992px, 960px if the viewport width is ≥992px but <1200px, 1140px if the viewport width is ≥1200px but <1400px, and 1320px if the viewport width is ≥1400px. You can simply use the .container class to create a responsive, fixed-width container. The width of the container will change at different breakpoints or screen sizes. You can use the .container-fluid class to create a full width container. The width of the fluid container will always be 100% irrespective of the devices or screen sizes.

## Bootstrap Grid System

Bootstrap grid system provides an easy and powerful way to create responsive layouts of all shapes and sizes. It is built with flexbox with mobile-first approach. Also, it is fully responsive and uses twelve column system (12 columns available per row) and six default responsive tiers. Features Bootstrap Grid System X-Small (xs) <576px Small (sm) ≥576px Medium (md) ≥768px Large (lg) ≥992px X-Large (xl) ≥1200px XX-Large (xxl) ≥1400px Container max-width None (auto) 540px 720px 960px 1140px 1320px Class prefix .col- .col-sm- .col-md- .col-lg- .col-xl- .col-xxl- Number of columns 12 Gutter width 1.5rem (.75rem on left and right) Custom gutters Yes Nestable Yes Column ordering Yes

## Bootstrap Responsive Layout

Responsive web design is a process of designing and building websites to provide better accessibility and optimal viewing experience to the user by optimizing it for different devices. With the growing trend of smart phones and tablets, it has become almost unavoidable to ignore the optimization of sites for mobile devices. Responsive web design is a preferable alternative and an efficient way to target a wide range of devices with much less efforts. Responsive layouts automatically adjust and adapts to any device screen size, whether it is a desktop, a laptop, a tablet, or a mobile phone. Bootstrap Forms HTML forms are an integral part of the web pages and applications, but creating the form layouts or styling the form controls manually one by one using CSS are often boring and tedious. Bootstrap greatly simplifies the process of styling and alignment of form controls like labels, input fields, selectboxes, textareas, buttons, etc. through predefined set of classes.

## Bootstrap Fixed Layout

With Bootstrap you can still create web page layouts based on fixed number of pixels, however the container width vary depending on the viewport width and the layout is responsive too. The process of creating the fixed yet responsive layout basically starts with the .container class. After that you can create rows with the .row class to wrap the horizontal groups of columns. Rows must be placed within a .container for proper alignment and padding.

## Bootstrap Fluid Layout

In Bootstrap you can use the class .container-fluid to create fluid layouts to utilize the 100% width of the viewport across all devices (extra small, small, medium, large, extra large, and extra-extra large). The class .container-fluid simply applies the width: 100% instead of different width for different viewport sizes. However, the layout will still responsive and you can use the grid classes as usual.

## Bootstrap Icons

Bootstrap now includes over 1,300 high quality icons, which are available in SVGs, SVG sprite, or web fonts format. You can use them with or without Bootstrap in any project. The advantage of using font icons is, you can create icons of any color just through applying the CSS color property. Also, to change the size of icons you can simply use the CSS font-size property.

## Bootstrap Images

Images are very common in modern web design. So styling images and placing it properly on the web pages is very important for improving the user experience. Using the Bootstrap built-in classes you can easily style images such as making the round cornered or circular images, or give them effect like thumbnails.

## The @keyframes Rule

When you specify CSS styles inside the @keyframes rule, the animation will gradually change from the current style to the new style at certain times.

To get an animation to work, you must bind the animation to an element.


