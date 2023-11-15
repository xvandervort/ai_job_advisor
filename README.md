# AI Job Advisor

The jupyter notebook included here contains demonstration code for asking ChatGPT for advice in getting a job in the growing AI field. 

## Dependencies

This notebook has been shown to work with the following Jupyter core packages.

* IPython          : 8.12.3
* ipykernel        : 6.26.0
* ipywidgets       : 8.1.1
* jupyter_client   : 8.6.0
* jupyter_core     : 5.5.0
* jupyter_server   : 2.10.0
* jupyterlab       : 4.0.8
* nbclient         : 0.9.0
* nbconvert        : 7.11.0
* nbformat         : 5.9.2
* notebook         : 7.0.6
* qtconsole        : 5.5.0
* traitlets        : 5.13.0

Also

* Python 3.8.10
* openai 1.2.4

An earlier version of this code made with lower versions of everything was incompatible with this environment. 

## USAGE

* Install the requirements.
  * If you already have a compatible version of jupyter notebook installed just install 'openai.'
    * `pip install openai==1.2.4`
  * Or you can run `pip install -r requirements.txt`
    * At your own risk. It's quite extensive. 
      * I suggest using an isoltated environment if you go this route.

* Start jupyter notebook with `jupyter notebook`

* Navigate to directory where the notebook (ai_job_advisor.ipynb) is.

* Best practice: Instead of opening the notebook, make a copy and play around with that, rather than with the original.

### In the notebook

* Insert your own OpenAI API key where it says to.

* If you want a different model than gpt-3.5-turbo, update it to reflect your preferred choice.

* Run the cells from yop yo bottom __one at a time__. Two of them require user input and the final one needs that input to run. So if you try to run the entire notebook, there will be errors.

## Discussion

This is an experiment. The results so far are mixed. More information on the website listed below.

Note that the provided version of this notebook contains some not at all useful sample data, just for illustrative purposes.

## Contributing

Sure. Put in a pull request if you want. I don't guaranty that I'll do anything about it but I don't guaranty that I won't, either.

## Self-Promotion

Dave Vandervort is a consultant who can help your start up or small business do a better job of integrating LLMs into your products, services or workflows. Until LLM's are superseded by something even more impressive. Then I guess I'll have to learn some brand new tech! (Actually, sounds like fun)

* __Website__: [Insight Forge LLC](https://www.insfor.net)
* __Contact form__: [Contact Me](https://forms.gle/o8MA4nCYrwwKRscRA)