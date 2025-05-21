# Design Guidelines

{
  "designGuidelines": {
    "colorSystem": {
      "primary": "#4A90E2",
      "secondary": "#50E3C2",
      "accent": "#F5A623",
      "success": "#7ED321",
      "error": "#D0021B",
      "warning": "#F8E71C",
      "background": "#FFFFFF",
      "surface": "#F0F2F5",
      "text": {
        "primary": "#333333",
        "secondary": "#666666",
        "disabled": "#9B9B9B"
      }
    },
    "typography": {
      "fontFamilies": {
        "primary": "'Roboto', sans-serif",
        "secondary": "'Montserrat', sans-serif"
      },
      "fontSizes": {
        "title": "24px",
        "subtitle": "18px",
        "body": "14px",
        "caption": "12px"
      },
      "lineHeights": {
        "title": "32px",
        "subtitle": "24px",
        "body": "20px",
        "caption": "16px"
      },
      "fontWeights": {
        "regular": "400",
        "medium": "500",
        "bold": "700"
      }
    },
    "spacing": {
      "marginAndPadding": {
        "small": "8px",
        "medium": "16px",
        "large": "24px",
        "extraLarge": "32px"
      },
      "gridSystem": "12-column",
      "componentSpacing": "16px"
    },
    "components": {
      "buttonStyles": {
        "default": {
          "backgroundColor": "#4A90E2",
          "color": "#FFFFFF",
          "padding": "12px 24px",
          "borderRadius": "4px"
        },
        "hover": {
          "backgroundColor": "#328FE2",
          "color": "#FFFFFF"
        }
      },
      "inputStyles": {
        "default": {
          "border": "1px solid #D9D9D9",
          "padding": "8px 16px",
          "borderRadius": "4px"
        },
        "focus": {
          "border": "2px solid #4A90E2"
        },
        "error": {
          "border": "2px solid #D0021B"
        }
      },
      "cardStyles": {
        "default": {
          "boxShadow": "0 2px 4px 0 rgba(0,0,0,0.1)",
          "margin": "16px",
          "padding": "16px",
          "borderRadius": "8px"
        }
      },
      "formStyles": {
        "label": {
          "display": "block",
          "marginBottom": "8px"
        },
        "input": {
          "marginBottom": "16px"
        }
      },
      "navigationStyles": {
        "navBar": {
          "backgroundColor": "#FFFFFF",
          "color": "#333333",
          "borderBottom": "1px solid #E1E1E1"
        },
        "navItem": {
          "padding": "16px 24px",
          "hover": {
            "backgroundColor": "#F0F2F5"
          }
        }
      }
    },
    "animations": {
      "transitions": "ease-out 0.3s",
      "hoverEffects": "scale(1.05)",
      "loadingStates": {
        "spinner": "rotate(360, 2s, infinite)"
      },
      "pageTransitions": "fade-in 0.5s"
    },
    "responsiveDesign": {
      "breakpoints": {
        "small": "600px",
        "medium": "900px",
        "large": "1200px",
        "extraLarge": "1800px"
      },
      "mobileFirstApproach": true,
      "gridSystem": {
        "small": "4-column",
        "medium": "8-column",
        "large": "12-column"
      },
      "componentAdaptations": {
        "navBar": {
          "small": {
            "position": "fixed",
            "bottom": "0",
            "width": "100%",
            "height": "60px",
            "display": "flex",
            "justifyContent": "space-around",
            "alignItems": "center"
          },
          "medium": {
            "position": "static",
            "height": "auto",
            "display": "block"
          }
        }
      }
    }
  },
  "pages": {
    "loginPage": {
      "elements": [
        "form containing inputs for email and password, and a submit button."
      ],
      "layoutRecommendations": {
        "formAlignment": "center",
        "verticalSpacing": "medium"
      }
    },
    "productDetailPage": {
      "elements": [
        "product images",
        "product title",
        "product description",
        "price",
        "add to cart button"
      ],
      "layoutRecommendations": {
        "imageGallery": "left or top",
        "informationSection": "right or below the image gallery"
      }
    },
    "myAccountPage": {
      "elements": [
        "navigation bar for account sections",
        "section for personal information",
        "section for order history",
        "logout button"
      ],
      "layoutRecommendations": {
        "navigationBar": "vertical on the left side",
        "contentAlignment": "left with ample spacing"
      }
    }
  }
}