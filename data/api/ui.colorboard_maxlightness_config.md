maxLightness
=============


@short:sets the end value of lightness for the default color palette
	

@type: number
@example:


@template:	api_config
@relatedapi:
	api/ui.colorboard_minlightness_config.md
@related:
	desktop/colorboard.md
@descr:
The default palette has a gradient background, lightness of which changes from **minLightness** to **maxLightness**.

	
    //the default values of parameters
    minLightness:0.15,
	maxLightness:1
        
{{note 
The parameter is ignored in case of using custom color palettes
}}