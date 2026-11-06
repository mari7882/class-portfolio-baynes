Initial Audit score: Page Speed Insights
Mobile Display Score: 87
    Issues:
        1. Background and foreground colors do not have a sufficient contrast ratio.
        2. Touch targets do not have sufficient size or spacing.
Desktop Display Score: 93
    Issues:
        1. Background and foreground colors do not have a sufficient contrast ratio.

Accessibility Updates
    Contrast Ratio:
        1. For the About section backgrond color, I made the color darker so users can read it better.
            background: rgb(31, 119, 219);
        2. In CSS I made the h3 color darker so that it is easier to read.
        3. I also made the secondary-bg darker for the white color fonts.
            rgb(9, 152, 209)

        1. & 3. UPDATE: i made the color for the secondary-bg back to the original color and made the text black to improve contrast
        
        4. For the GBM website link, I adjusted the color by adding a class to it in my html and then editing the color and underline design with CSS
            .gbm-site 
                 color: black;
                     font-weight: bold;
                    text-decoration: underline wavy;
    Touch Targets:
        1. i made the height of the navigation bar to 35px so its easier to click the categories'
        2. I created more padding space and added inline-block


